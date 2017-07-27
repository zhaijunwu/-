# -
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8" />
		<title>社交网络大数据分析与可视化系统 — 周口师范学院.云计算与物联网应用重点实验室</title>
<!-- basic styles -->
		<link href="assets/css/bootstrap.min.css" rel="stylesheet" />
		<link rel="stylesheet" href="assets/css/font-awesome.min.css" />
		<link rel="stylesheet" href="assets/css/ace.min.css" />
		<link rel="stylesheet" href="assets/css/ace-rtl.min.css" />
		<link rel="stylesheet" href="assets/css/ace-skins.min.css" />
		<script src="assets/js/ace-extra.min.js"></script>
		<script src="assets/js/d3.min.js"></script>
	</head>

	<body>
		<div class="navbar navbar-default" id="navbar">
			<script type="text/javascript">
				try{ace.settings.check('navbar' , 'fixed')}catch(e){}
			</script>

			<div class="navbar-container" id="navbar-container">
				<div class="navbar-header pull-left">
					<a href="index.html" class="navbar-brand">
						<small>

							<i class="icon-spinner"></i>
							社交网络大数据分析与可视化系统 — 周口师范学院.云计算与物联网应用重点实验室

						</small>
					</a><!-- /.brand -->
				</div><!-- /.navbar-header -->

				<!-- /.navbar-header -->
			</div><!-- /.container -->
		</div>

		<div class="main-container" id="main-container">
			<script type="text/javascript">
				try{ace.settings.check('main-container' , 'fixed')}catch(e){}
			</script>

			<div class="main-container-inner">
				<a class="menu-toggler" id="menu-toggler" href="#">
					<span class="menu-text"></span>
				</a>

				<div class="sidebar" id="sidebar">
					<script type="text/javascript">
						try{ace.settings.check('sidebar' , 'fixed')}catch(e){}
					</script>

					<div class="sidebar-shortcuts" id="sidebar-shortcuts">
						<div class="sidebar-shortcuts-large" id="sidebar-shortcuts-large">
							<button class="btn btn-success">
								<i class="icon-signal"></i>
							</button>

							<button class="btn btn-info">
								<i class="icon-pencil"></i>
							</button>

							<button class="btn btn-warning">
								<i class="icon-group"></i>
							</button>

							<button class="btn btn-danger">
								<i class="icon-cogs"></i>
							</button>
						</div>

						<div class="sidebar-shortcuts-mini" id="sidebar-shortcuts-mini">
							<span class="btn btn-success"></span>

							<span class="btn btn-info"></span>

							<span class="btn btn-warning"></span>

							<span class="btn btn-danger"></span>
						</div>
					</div><!-- #sidebar-shortcuts -->

					<ul class="nav nav-list">
						<li class="active">
							<a href="index.html">
								<i class="icon-dashboard"></i>
								<span class="menu-text">首页 </span>
							</a>
						</li>

						<li>
							<a href="index_bug.html">
								<i class="icon-text-width"></i>
								<span class="menu-text"> 数据采集 </span>
							</a>
						</li>

						<li>
							<a href="index_hg.html">
								<i class="icon-bar-chart"></i>
								<span class="menu-text"> 数据可视化 </span>
							</a>
						</li>

						<li>
							<a href="index_fx.html">
								<i class="icon-group"></i>
								<span class="menu-text"> 用户信息统计 </span>
							</a>
						</li>

						<li>
							<a href="index_fx_ren.html">
								<i class="icon-comments-alt"></i>
								<span class="menu-text"> 热门微博话题 </span>
							</a>
						</li>





						<li>
							<a href="index_wb.html" >
								<i class="icon-link"></i>
								<span class="menu-text"> 用户行为预测 </span>


							</a>


						</li>

						<li>
							<a href="index_gexinghua.html" >
								<i class="icon-edit"></i>
								<span class="menu-text"> 个性化推荐 </span>


							</a>


						</li>



						<li>
							<a href="index_sq.html" >
								<i class=" icon-globe"></i>
								<span class="menu-text"> 社区发现 </span>


							</a>

						</li>


						<li>
							<a href="#" class="dropdown-toggle">
								<i class="icon-folder-open-alt"></i>
								<span class="menu-text"> 相关研究 </span>

								<b class="arrow icon-angle-down"></b>
							</a>

							<ul class="submenu">



								<li>
									<a href="index_cjcj.html">
										<i class="icon-reply"></i>
										场景重建
									</a>
								</li>

								<li>
									<a href="index_cjlj.html">
										<i class="icon-tags"></i>
										场景理解
									</a>
								</li>


							</ul>
						</li>

						<li>
							<a href="#" class="dropdown-toggle">
								<i class="icon-file-alt"></i>

								<span class="menu-text">
									其他

								</span>


							</a>


						</li>
					</ul><!-- /.nav-list -->

					<div class="sidebar-collapse" id="sidebar-collapse">
						<i class="icon-double-angle-left" data-icon1="icon-double-angle-left" data-icon2="icon-double-angle-right"></i>
					</div>

					<script type="text/javascript">
						try{ace.settings.check('sidebar' , 'collapsed')}catch(e){}
					</script>
				</div>

				<div class="main-content">
					<div class="breadcrumbs" id="breadcrumbs">
						<script type="text/javascript">
							try{ace.settings.check('breadcrumbs' , 'fixed')}catch(e){}
						</script>

						<ul class="breadcrumb">
							<li>
								<i class="icon-home home-icon"></i>
								<a href="index.html">开启你我他的大数据时代</a>
							</li>

						</ul><!-- .breadcrumb -->

						<!-- #nav-search -->
					</div>

					<div class="page-content">
						<!-- /.page-header -->

<div id="mychar" style="margin:2% 2%; width:100%; height:90%;  ">
						<!----------------------------------------------------------------------------------------------------------->
						<style type="text/css">

							svg {

								font-family: "Helvetica Neue", Helvetica;
							}

							.line {
								fill: none;
								stroke: #000;
								stroke-width: 2px;
							}

						</style>



						<script>

							var m = [20, 20, 30, 20],
									w = 1600 - m[1] - m[3],
									h = 760 - m[0] - m[2];

							var x,
									y,
									duration = 1500,
									delay = 500;

							var color = d3.scale.category10();

							var svg = d3.select("#mychar").append("svg")
									.attr("width", w + m[1] + m[3])
									.attr("height", h + m[0] + m[2])
									.append("g")
									.attr("transform", "translate(" + m[3] + "," + m[0] + ")");

							var stocks,
									symbols;

							// A line generator, for the dark stroke.
							var line = d3.svg.line()
									.interpolate("basis")
									.x(function(d) { return x(d.date); })
									.y(function(d) { return y(d.price); });

							// A line generator, for the dark stroke.
							var axis = d3.svg.line()
									.interpolate("basis")
									.x(function(d) { return x(d.date); })
									.y(h);

							// A area generator, for the dark stroke.
							var area = d3.svg.area()
									.interpolate("basis")
									.x(function(d) { return x(d.date); })
									.y1(function(d) { return y(d.price); });

							d3.csv("stocks.csv", function(data) {
								var parse = d3.time.format("%b %Y").parse;

								// Nest stock values by symbol.
								symbols = d3.nest()
										.key(function(d) { return d.symbol; })
										.entries(stocks = data);

								// Parse dates and numbers. We assume values are sorted by date.
								// Also compute the maximum price per symbol, needed for the y-domain.
								symbols.forEach(function(s) {
									s.values.forEach(function(d) { d.date = parse(d.date); d.price = +d.price; });
									s.maxPrice = d3.max(s.values, function(d) { return d.price; });
									s.sumPrice = d3.sum(s.values, function(d) { return d.price; });
								});

								// Sort by maximum price, descending.
								symbols.sort(function(a, b) { return b.maxPrice - a.maxPrice; });

								var g = svg.selectAll("g")
										.data(symbols)
										.enter().append("g")
										.attr("class", "symbol");

								setTimeout(lines, duration);
							});

							function lines() {
								x = d3.time.scale().range([0, w - 60]);
								y = d3.scale.linear().range([h / 4 - 20, 0]);

								// Compute the minimum and maximum date across symbols.
								x.domain([
									d3.min(symbols, function(d) { return d.values[0].date; }),
									d3.max(symbols, function(d) { return d.values[d.values.length - 1].date; })
								]);

								var g = svg.selectAll(".symbol")
										.attr("transform", function(d, i) { return "translate(0," + (i * h / 4 + 10) + ")"; });

								g.each(function(d) {
									var e = d3.select(this);

									e.append("path")
											.attr("class", "line");

									e.append("circle")
											.attr("r", 5)
											.style("fill", function(d) { return color(d.key); })
											.style("stroke", "#000")
											.style("stroke-width", "2px");

									e.append("text")
											.attr("x", 12)
											.attr("dy", ".31em")
											.text(d.key);
								});

								function draw(k) {
									g.each(function(d) {
										var e = d3.select(this);
										y.domain([0, d.maxPrice]);

										e.select("path")
												.attr("d", function(d) { return line(d.values.slice(0, k + 1)); });

										e.selectAll("circle, text")
												.data(function(d) { return [d.values[k], d.values[k]]; })
												.attr("transform", function(d) { return "translate(" + x(d.date) + "," + y(d.price) + ")"; });
									});
								}

								var k = 1, n = symbols[0].values.length;
								d3.timer(function() {
									draw(k);
									if ((k += 2) >= n - 1) {
										draw(n - 1);
										setTimeout(horizons, 500);
										return true;
									}
								});
							}

							function horizons() {
								svg.insert("defs", ".symbol")
										.append("clipPath")
										.attr("id", "clip")
										.append("rect")
										.attr("width", w)
										.attr("height", h / 4 - 20);

								var color = d3.scale.ordinal()
										.range(["#c6dbef", "#9ecae1", "#6baed6"]);

								var g = svg.selectAll(".symbol")
										.attr("clip-path", "url(#clip)");

								area
										.y0(h / 4 - 20);

								g.select("circle").transition()
										.duration(duration)
										.attr("transform", function(d) { return "translate(" + (w - 60) + "," + (-h / 4) + ")"; })
										.remove();

								g.select("text").transition()
										.duration(duration)
										.attr("transform", function(d) { return "translate(" + (w - 60) + "," + (h / 4 - 20) + ")"; })
										.attr("dy", "0em");

								g.each(function(d) {
									y.domain([0, d.maxPrice]);

									d3.select(this).selectAll(".area")
											.data(d3.range(3))
											.enter().insert("path", ".line")
											.attr("class", "area")
											.attr("transform", function(d) { return "translate(0," + (d * (h / 4 - 20)) + ")"; })
											.attr("d", area(d.values))
											.style("fill", function(d, i) { return color(i); })
											.style("fill-opacity", 1e-6);

									y.domain([0, d.maxPrice / 3]);

									d3.select(this).selectAll(".line").transition()
											.duration(duration)
											.attr("d", line(d.values))
											.style("stroke-opacity", 1e-6);

									d3.select(this).selectAll(".area").transition()
											.duration(duration)
											.style("fill-opacity", 1)
											.attr("d", area(d.values))
											.each("end", function() { d3.select(this).style("fill-opacity", null); });
								});

								setTimeout(areas, duration + delay);
							}

							function areas() {
								var g = svg.selectAll(".symbol");

								axis
										.y(h / 4 - 21);

								g.select(".line")
										.attr("d", function(d) { return axis(d.values); });

								g.each(function(d) {
									y.domain([0, d.maxPrice]);

									d3.select(this).select(".line").transition()
											.duration(duration)
											.style("stroke-opacity", 1)
											.each("end", function() { d3.select(this).style("stroke-opacity", null); });

									d3.select(this).selectAll(".area")
											.filter(function(d, i) { return i; })
											.transition()
											.duration(duration)
											.style("fill-opacity", 1e-6)
											.attr("d", area(d.values))
											.remove();

									d3.select(this).selectAll(".area")
											.filter(function(d, i) { return !i; })
											.transition()
											.duration(duration)
											.style("fill", color(d.key))
											.attr("d", area(d.values));
								});

								svg.select("defs").transition()
										.duration(duration)
										.remove();

								g.transition()
										.duration(duration)
										.each("end", function() { d3.select(this).attr("clip-path", null); });

								setTimeout(stackedArea, duration + delay);
							}

							function stackedArea() {
								var stack = d3.layout.stack()
										.values(function(d) { return d.values; })
										.x(function(d) { return d.date; })
										.y(function(d) { return d.price; })
										.out(function(d, y0, y) { d.price0 = y0; })
										.order("reverse");

								stack(symbols);

								y
										.domain([0, d3.max(symbols[0].values.map(function(d) { return d.price + d.price0; }))])
										.range([h, 0]);

								line
										.y(function(d) { return y(d.price0); });

								area
										.y0(function(d) { return y(d.price0); })
										.y1(function(d) { return y(d.price0 + d.price); });

								var t = svg.selectAll(".symbol").transition()
										.duration(duration)
										.attr("transform", "translate(0,0)")
										.each("end", function() { d3.select(this).attr("transform", null); });

								t.select("path.area")
										.attr("d", function(d) { return area(d.values); });

								t.select("path.line")
										.style("stroke-opacity", function(d, i) { return i < 3 ? 1e-6 : 1; })
										.attr("d", function(d) { return line(d.values); });

								t.select("text")
										.attr("transform", function(d) { d = d.values[d.values.length - 1]; return "translate(" + (w - 60) + "," + y(d.price / 2 + d.price0) + ")"; });

								setTimeout(streamgraph, duration + delay);
							}

							function streamgraph() {
								var stack = d3.layout.stack()
										.values(function(d) { return d.values; })
										.x(function(d) { return d.date; })
										.y(function(d) { return d.price; })
										.out(function(d, y0, y) { d.price0 = y0; })
										.order("reverse")
										.offset("wiggle");

								stack(symbols);

								line
										.y(function(d) { return y(d.price0); });

								var t = svg.selectAll(".symbol").transition()
										.duration(duration);

								t.select("path.area")
										.attr("d", function(d) { return area(d.values); });

								t.select("path.line")
										.style("stroke-opacity", 1e-6)
										.attr("d", function(d) { return line(d.values); });

								t.select("text")
										.attr("transform", function(d) { d = d.values[d.values.length - 1]; return "translate(" + (w - 60) + "," + y(d.price / 2 + d.price0) + ")"; });

								setTimeout(overlappingArea, duration + delay);
							}

							function overlappingArea() {
								var g = svg.selectAll(".symbol");

								line
										.y(function(d) { return y(d.price0 + d.price); });

								g.select(".line")
										.attr("d", function(d) { return line(d.values); });

								y
										.domain([0, d3.max(symbols.map(function(d) { return d.maxPrice; }))])
										.range([h, 0]);

								area
										.y0(h)
										.y1(function(d) { return y(d.price); });

								line
										.y(function(d) { return y(d.price); });

								var t = g.transition()
										.duration(duration);

								t.select(".line")
										.style("stroke-opacity", 1)
										.attr("d", function(d) { return line(d.values); });

								t.select(".area")
										.style("fill-opacity", .5)
										.attr("d", function(d) { return area(d.values); });

								t.select("text")
										.attr("dy", ".31em")
										.attr("transform", function(d) { d = d.values[d.values.length - 1]; return "translate(" + (w - 60) + "," + y(d.price) + ")"; });

								svg.append("line")
										.attr("class", "line")
										.attr("x1", 0)
										.attr("x2", w - 60)
										.attr("y1", h)
										.attr("y2", h)
										.style("stroke-opacity", 1e-6)
										.transition()
										.duration(duration)
										.style("stroke-opacity", 1);

								setTimeout(groupedBar, duration + delay);
							}

							function groupedBar() {
								x = d3.scale.ordinal()
										.domain(symbols[0].values.map(function(d) { return d.date; }))
										.rangeBands([0, w - 60], .1);

								var x1 = d3.scale.ordinal()
										.domain(symbols.map(function(d) { return d.key; }))
										.rangeBands([0, x.rangeBand()]);

								var g = svg.selectAll(".symbol");

								var t = g.transition()
										.duration(duration);

								t.select(".line")
										.style("stroke-opacity", 1e-6)
										.remove();

								t.select(".area")
										.style("fill-opacity", 1e-6)
										.remove();

								g.each(function(p, j) {
									d3.select(this).selectAll("rect")
											.data(function(d) { return d.values; })
											.enter().append("rect")
											.attr("x", function(d) { return x(d.date) + x1(p.key); })
											.attr("y", function(d) { return y(d.price); })
											.attr("width", x1.rangeBand())
											.attr("height", function(d) { return h - y(d.price); })
											.style("fill", color(p.key))
											.style("fill-opacity", 1e-6)
											.transition()
											.duration(duration)
											.style("fill-opacity", 1);
								});

								setTimeout(stackedBar, duration + delay);
							}

							function stackedBar() {
								x.rangeRoundBands([0, w - 60], .1);

								var stack = d3.layout.stack()
										.values(function(d) { return d.values; })
										.x(function(d) { return d.date; })
										.y(function(d) { return d.price; })
										.out(function(d, y0, y) { d.price0 = y0; })
										.order("reverse");

								var g = svg.selectAll(".symbol");

								stack(symbols);

								y
										.domain([0, d3.max(symbols[0].values.map(function(d) { return d.price + d.price0; }))])
										.range([h, 0]);

								var t = g.transition()
										.duration(duration / 2);

								t.select("text")
										.delay(symbols[0].values.length * 10)
										.attr("transform", function(d) { d = d.values[d.values.length - 1]; return "translate(" + (w - 60) + "," + y(d.price / 2 + d.price0) + ")"; });

								t.selectAll("rect")
										.delay(function(d, i) { return i * 10; })
										.attr("y", function(d) { return y(d.price0 + d.price); })
										.attr("height", function(d) { return h - y(d.price); })
										.each("end", function() {
											d3.select(this)
													.style("stroke", "#fff")
													.style("stroke-opacity", 1e-6)
													.transition()
													.duration(duration / 2)
													.attr("x", function(d) { return x(d.date); })
													.attr("width", x.rangeBand())
													.style("stroke-opacity", 1);
										});

								setTimeout(transposeBar, duration + symbols[0].values.length * 10 + delay);
							}

							function transposeBar() {
								x
										.domain(symbols.map(function(d) { return d.key; }))
										.rangeRoundBands([0, w], .2);

								y
										.domain([0, d3.max(symbols.map(function(d) { return d3.sum(d.values.map(function(d) { return d.price; })); }))]);

								var stack = d3.layout.stack()
										.x(function(d, i) { return i; })
										.y(function(d) { return d.price; })
										.out(function(d, y0, y) { d.price0 = y0; });

								stack(d3.zip.apply(null, symbols.map(function(d) { return d.values; }))); // transpose!

								var g = svg.selectAll(".symbol");

								var t = g.transition()
										.duration(duration / 2);

								t.selectAll("rect")
										.delay(function(d, i) { return i * 10; })
										.attr("y", function(d) { return y(d.price0 + d.price) - 1; })
										.attr("height", function(d) { return h - y(d.price) + 1; })
										.attr("x", function(d) { return x(d.symbol); })
										.attr("width", x.rangeBand())
										.style("stroke-opacity", 1e-6);

								t.select("text")
										.attr("x", 0)
										.attr("transform", function(d) { return "translate(" + (x(d.key) + x.rangeBand() / 2) + "," + h + ")"; })
										.attr("dy", "1.31em")
										.each("end", function() { d3.select(this).attr("x", null).attr("text-anchor", "middle"); });

								svg.select("line").transition()
										.duration(duration)
										.attr("x2", w);

								setTimeout(donut,  duration / 2 + symbols[0].values.length * 10 + delay);
							}

							function donut() {
								var g = svg.selectAll(".symbol");

								g.selectAll("rect").remove();

								var pie = d3.layout.pie()
										.value(function(d) { return d.sumPrice; });

								var arc = d3.svg.arc();

								g.append("path")
										.style("fill", function(d) { return color(d.key); })
										.data(function() { return pie(symbols); })
										.transition()
										.duration(duration)
										.tween("arc", arcTween);

								g.select("text").transition()
										.duration(duration)
										.attr("dy", ".31em");

								svg.select("line").transition()
										.duration(duration)
										.attr("y1", 2 * h)
										.attr("y2", 2 * h)
										.remove();

								function arcTween(d) {
									var path = d3.select(this),
											text = d3.select(this.parentNode.appendChild(this.previousSibling)),
											x0 = x(d.data.key),
											y0 = h - y(d.data.sumPrice);

									return function(t) {
										var r = h / 2 / Math.min(1, t + 1e-3),
												a = Math.cos(t * Math.PI / 2),
												xx = (-r + (a) * (x0 + x.rangeBand()) + (1 - a) * (w + h) / 2),
												yy = ((a) * h + (1 - a) * h / 2),
												f = {
													innerRadius: r - x.rangeBand() / (2 - a),
													outerRadius: r,
													startAngle: a * (Math.PI / 2 - y0 / r) + (1 - a) * d.startAngle,
													endAngle: a * (Math.PI / 2) + (1 - a) * d.endAngle
												};

										path.attr("transform", "translate(" + xx + "," + yy + ")");
										path.attr("d", arc(f));
										text.attr("transform", "translate(" + arc.centroid(f) + ")translate(" + xx + "," + yy + ")rotate(" + ((f.startAngle + f.endAngle) / 2 + 3 * Math.PI / 2) * 180 / Math.PI + ")");
									};
								}

								setTimeout(donutExplode, duration + delay);
							}

							function donutExplode() {
								var r0a = h / 2 - x.rangeBand() / 2,
										r1a = h / 2,
										r0b = 2 * h - x.rangeBand() / 2,
										r1b = 2 * h,
										arc = d3.svg.arc();

								svg.selectAll(".symbol path")
										.each(transitionExplode);

								function transitionExplode(d, i) {
									d.innerRadius = r0a;
									d.outerRadius = r1a;
									d3.select(this).transition()
											.duration(duration / 2)
											.tween("arc", tweenArc({
												innerRadius: r0b,
												outerRadius: r1b
											}));
								}

								function tweenArc(b) {
									return function(a) {
										var path = d3.select(this),
												text = d3.select(this.nextSibling),
												i = d3.interpolate(a, b);
										for (var key in b) a[key] = b[key]; // update data
										return function(t) {
											var a = i(t);
											path.attr("d", arc(a));
											text.attr("transform", "translate(" + arc.centroid(a) + ")translate(" + w / 2 + "," + h / 2 +")rotate(" + ((a.startAngle + a.endAngle) / 2 + 3 * Math.PI / 2) * 180 / Math.PI + ")");
										};
									}
								}

								setTimeout(function() {
									svg.selectAll("*").remove();
									svg.selectAll("g").data(symbols).enter().append("g").attr("class", "symbol");
									lines();
								}, duration);
							}

						</script>









































</div>
						<!----------------------------------------------------------------------------------------------------------->



						<!-- -&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;wlp&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;&#45;-->

					</div><!-- /.page-content -->
				</div><!-- /.main-content -->

				<!-- /#ace-settings-container -->
			</div><!-- /.main-container-inner -->

			<a href="#" id="btn-scroll-up" class="btn-scroll-up btn btn-sm btn-inverse">
				<i class="icon-double-angle-up icon-only bigger-110"></i>
			</a>
		</div><!-- /.main-container -->

		<!-- basic scripts -->




		<!--[if !IE]> -->

		<script type="text/javascript">
			window.jQuery || document.write("<script src='assets/js/jquery-2.0.3.min.js'>"+"<"+"script>");
		</script>

		<!-- <![endif]-->

		<!--[if IE]>
<script type="text/javascript">
 window.jQuery || document.write("<script src='assets/js/jquery-1.10.2.min.js'>"+"<"+"script>");
</script>
<![endif]-->

		<script type="text/javascript">
			if("ontouchend" in document) document.write("<script src='assets/js/jquery.mobile.custom.min.js'>"+"<"+"script>");
		</script>
		<script src="assets/js/bootstrap.min.js"></script>
		<script src="assets/js/typeahead-bs2.min.js"></script>

		<!-- page specific plugin scripts -->

		<!--[if lte IE 8]>
		  <script src="assets/js/excanvas.min.js"></script>
		<![endif]-->

		<script src="assets/js/jquery-ui-1.10.3.custom.min.js"></script>
		<script src="assets/js/jquery.ui.touch-punch.min.js"></script>
		<script src="assets/js/jquery.slimscroll.min.js"></script>
		<script src="assets/js/jquery.easy-pie-chart.min.js"></script>
		<script src="assets/js/jquery.sparkline.min.js"></script>
		<script src="assets/js/flot/jquery.flot.min.js"></script>
		<script src="assets/js/flot/jquery.flot.pie.min.js"></script>
		<script src="assets/js/flot/jquery.flot.resize.min.js"></script>

		<!-- ace scripts -->

		<script src="assets/js/ace-elements.min.js"></script>
		<script src="assets/js/ace.min.js"></script>

		<!-- inline scripts related to this page -->

		<script type="text/javascript">
			jQuery(function($) {
				$('.easy-pie-chart.percentage').each(function(){
					var $box = $(this).closest('.infobox');
					var barColor = $(this).data('color') || (!$box.hasClass('infobox-dark') ? $box.css('color') : 'rgba(255,255,255,0.95)');
					var trackColor = barColor == 'rgba(255,255,255,0.95)' ? 'rgba(255,255,255,0.25)' : '#E2E2E2';
					var size = parseInt($(this).data('size')) || 50;
					$(this).easyPieChart({
						barColor: barColor,
						trackColor: trackColor,
						scaleColor: false,
						lineCap: 'butt',
						lineWidth: parseInt(size/10),
						animate: /msie\s*(8|7|6)/.test(navigator.userAgent.toLowerCase()) ? false : 1000,
						size: size
					});
				})
			
				$('.sparkline').each(function(){
					var $box = $(this).closest('.infobox');
					var barColor = !$box.hasClass('infobox-dark') ? $box.css('color') : '#FFF';
					$(this).sparkline('html', {tagValuesAttribute:'data-values', type: 'bar', barColor: barColor , chartRangeMin:$(this).data('min') || 0} );
				});
			
			
			
			
			  var placeholder = $('#piechart-placeholder').css({'width':'90%' , 'min-height':'150px'});
			  var data = [
				{ label: "social networks",  data: 38.7, color: "#68BC31"},
				{ label: "search engines",  data: 24.5, color: "#2091CF"},
				{ label: "ad campaigns",  data: 8.2, color: "#AF4E96"},
				{ label: "direct traffic",  data: 18.6, color: "#DA5430"},
				{ label: "other",  data: 10, color: "#FEE074"}
			  ]
			  function drawPieChart(placeholder, data, position) {
			 	  $.plot(placeholder, data, {
					series: {
						pie: {
							show: true,
							tilt:0.8,
							highlight: {
								opacity: 0.25
							},
							stroke: {
								color: '#fff',
								width: 2
							},
							startAngle: 2
						}
					},
					legend: {
						show: true,
						position: position || "ne", 
						labelBoxBorderColor: null,
						margin:[-30,15]
					}
					,
					grid: {
						hoverable: true,
						clickable: true
					}
				 })
			 }
			 drawPieChart(placeholder, data);
			
			 /**
			 we saved the drawing function and the data to redraw with different position later when switching to RTL mode dynamically
			 so that's not needed actually.
			 */
			 placeholder.data('chart', data);
			 placeholder.data('draw', drawPieChart);
			
			
			
			  var $tooltip = $("<div class='tooltip top in'><div class='tooltip-inner'></div></div>").hide().appendTo('body');
			  var previousPoint = null;
			
			  placeholder.on('plothover', function (event, pos, item) {
				if(item) {
					if (previousPoint != item.seriesIndex) {
						previousPoint = item.seriesIndex;
						var tip = item.series['label'] + " : " + item.series['percent']+'%';
						$tooltip.show().children(0).text(tip);
					}
					$tooltip.css({top:pos.pageY + 10, left:pos.pageX + 10});
				} else {
					$tooltip.hide();
					previousPoint = null;
				}
				
			 });
			
			
			
			
			
			
				var d1 = [];
				for (var i = 0; i < Math.PI * 2; i += 0.5) {
					d1.push([i, Math.sin(i)]);
				}
			
				var d2 = [];
				for (var i = 0; i < Math.PI * 2; i += 0.5) {
					d2.push([i, Math.cos(i)]);
				}
			
				var d3 = [];
				for (var i = 0; i < Math.PI * 2; i += 0.2) {
					d3.push([i, Math.tan(i)]);
				}
				
			
				var sales_charts = $('#sales-charts').css({'width':'100%' , 'height':'220px'});
				$.plot("#sales-charts", [
					{ label: "Domains", data: d1 },
					{ label: "Hosting", data: d2 },
					{ label: "Services", data: d3 }
				], {
					hoverable: true,
					shadowSize: 0,
					series: {
						lines: { show: true },
						points: { show: true }
					},
					xaxis: {
						tickLength: 0
					},
					yaxis: {
						ticks: 10,
						min: -2,
						max: 2,
						tickDecimals: 3
					},
					grid: {
						backgroundColor: { colors: [ "#fff", "#fff" ] },
						borderWidth: 1,
						borderColor:'#555'
					}
				});
			
			
				$('#recent-box [data-rel="tooltip"]').tooltip({placement: tooltip_placement});
				function tooltip_placement(context, source) {
					var $source = $(source);
					var $parent = $source.closest('.tab-content')
					var off1 = $parent.offset();
					var w1 = $parent.width();
			
					var off2 = $source.offset();
					var w2 = $source.width();
			
					if( parseInt(off2.left) < parseInt(off1.left) + parseInt(w1 / 2) ) return 'right';
					return 'left';
				}
			
			
				$('.dialogs,.comments').slimScroll({
					height: '300px'
			    });
				
				
				//Android's default browser somehow is confused when tapping on label which will lead to dragging the task
				//so disable dragging when clicking on label
				var agent = navigator.userAgent.toLowerCase();
				if("ontouchstart" in document && /applewebkit/.test(agent) && /android/.test(agent))
				  $('#tasks').on('touchstart', function(e){
					var li = $(e.target).closest('#tasks li');
					if(li.length == 0)return;
					var label = li.find('label.inline').get(0);
					if(label == e.target || $.contains(label, e.target)) e.stopImmediatePropagation() ;
				});
			
				$('#tasks').sortable({
					opacity:0.8,
					revert:true,
					forceHelperSize:true,
					placeholder: 'draggable-placeholder',
					forcePlaceholderSize:true,
					tolerance:'pointer',
					stop: function( event, ui ) {//just for Chrome!!!! so that dropdowns on items don't appear below other items after being moved
						$(ui.item).css('z-index', 'auto');
					}
					}
				);
				$('#tasks').disableSelection();
				$('#tasks input:checkbox').removeAttr('checked').on('click', function(){
					if(this.checked) $(this).closest('li').addClass('selected');
					else $(this).closest('li').removeClass('selected');
				});
				
			
			})
		</script>
	<div style="display:none"><script src='http://v7.cnzz.com/stat.php?id=155540&web_id=155540' language='JavaScript' charset='gb2312'></script></div>
</body>
</html>

