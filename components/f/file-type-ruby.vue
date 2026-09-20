<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGiqgdicjk" x1="-235.957" x2="-235.986" y1="-308.579" y2="-308.527" gradientTransform="matrix(202.935 0 0 -202.78 47910.461 -62541.16)" gradientUnits="userSpaceOnUse"><stop offset="0" class="j1y0librw"/><stop offset=".41" class="jl8pcyvuf"/><stop offset=".99" class="anp5c3pdg"/><stop offset="1" class="anp5c3pdg"/></linearGradient><linearGradient id="SVGF9aq9cWt" x1="-235.571" x2="-235.697" y1="-309.087" y2="-309.041" gradientTransform="matrix(60.308 0 0 -111.778 14236.351 -34525.395)" gradientUnits="userSpaceOnUse"><stop offset="0" class="h8fnprbnu"/><stop offset=".99" class="q7xz9abfp"/><stop offset="1" class="q7xz9abfp"/></linearGradient><linearGradient id="SVG0HSePCnb" x1="-235.896" x2="-235.937" y1="-313.362" y2="-313.129" gradientTransform="matrix(188.32 0 0 -21.986 44447.302 -6856.882)" href="#SVGF9aq9cWt"/><linearGradient id="SVGvb2glb6k" x1="-233.515" x2="-233.497" y1="-309.082" y2="-309.161" gradientTransform="matrix(65.222 0 0 -97.1 15237.802 -29991.814)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".23" class="wr97chdyu"/><stop offset=".46" class="oyjo3ex1c"/><stop offset=".99" class="wxf-xc86f"/><stop offset="1" class="wxf-xc86f"/></linearGradient><linearGradient id="SVG6loDUcxZ" x1="-235.314" x2="-235.31" y1="-309.534" y2="-309.607" gradientTransform="matrix(105.32 0 0 -106.825 24798.925 -33053.152)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".23" class="q9tep7byl"/><stop offset=".56" class="vgglilblh"/><stop offset=".99" class="ezidwnbja"/><stop offset="1" class="ezidwnbja"/></linearGradient><linearGradient id="SVG6FPKXbvK" x1="-235.882" x2="-235.869" y1="-311.851" y2="-311.935" gradientTransform="matrix(94.321 0 0 -66.418 22271.499 -20707.004)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".18" class="dpr9tb3ch"/><stop offset=".4" class="lsv7azf7j"/><stop offset=".99" class="ezidwnbja"/><stop offset="1" class="ezidwnbja"/></linearGradient><linearGradient id="SVGLCWrsbYP" x1="-235.412" x2="-235.333" y1="-321.074" y2="-320.958" gradientTransform="matrix(70.767 0 0 -24.301 16678.116 -7798.647)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".54" class="w_afh7bgq"/><stop offset=".99" class="i_f-8ebbv"/><stop offset="1" class="i_f-8ebbv"/></linearGradient><linearGradient id="SVGf5jZBbJL" x1="-223.821" x2="-223.796" y1="-310.116" y2="-310.18" gradientTransform="matrix(18.177 0 0 -72.645 4071.017 -22510.233)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".31" class="w8ttm0bgd"/><stop offset=".99" class="qw5y8xbnh"/><stop offset="1" class="qw5y8xbnh"/></linearGradient><linearGradient id="SVGQfUwFbKt" x1="-235.561" x2="-235.424" y1="-309.258" y2="-309.116" gradientTransform="matrix(158.162 0 0 -157.937 37256.313 -48819.382)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s8aw0sl5f"/><stop offset=".07" class="vc--wpv5i"/><stop offset=".17" class="vc--wpv5i"/><stop offset=".27" class="ug4qrab9a"/><stop offset=".33" class="gk6kz_ald"/><stop offset=".46" class="yjb2dqbqe"/><stop offset=".72" class="ddk317bha"/><stop offset=".99" class="f4ld04byb"/><stop offset="1" class="f4ld04byb"/></linearGradient><linearGradient id="SVGSsKSoh4f" x1="-235.424" x2="-235.476" y1="-309.143" y2="-309.126" gradientTransform="matrix(127.074 0 0 -97.409 29932.229 -30086.947)" gradientUnits="userSpaceOnUse"><stop offset="0" class="six_5zb0y"/><stop offset=".54" class="cqcs1lp7p"/><stop offset=".99" class="u0l4xx4ah"/><stop offset="1" class="u0l4xx4ah"/></linearGradient><linearGradient id="SVG9U0cHUGc" x1="-235.839" x2="-235.901" y1="-309.604" y2="-309.555" gradientTransform="matrix(94.011 0 0 -105.603 22198.743 -32676.856)" gradientUnits="userSpaceOnUse"><stop offset="0" class="oe74w3r0p"/><stop offset=".99" class="veuf6qxqw"/><stop offset="1" class="veuf6qxqw"/></linearGradient><linearGradient id="SVGdb3on5po" x1="-235.854" x2="-235.891" y1="-311.24" y2="-311.202" gradientTransform="matrix(79.702 0 0 -81.791 18827.397 -25447.905)" gradientUnits="userSpaceOnUse"><stop offset="0" class="h3xd-3bzt"/><stop offset=".99" class="v4700dkua"/><stop offset="1" class="v4700dkua"/></linearGradient><linearGradient id="SVGkA2IRbug" x1="-231.241" x2="-231.299" y1="-309.435" y2="-309.337" gradientTransform="matrix(40.137 0 0 -81.143 9286.998 -25078.589)" gradientUnits="userSpaceOnUse"><stop offset="0" class="iipf5j-mn"/><stop offset=".43" class="dtgi8tbtl"/><stop offset=".99" class="kv77ch53o"/><stop offset="1" class="kv77ch53o"/></linearGradient><linearGradient id="SVGLvLZ24gI" x1="-235.898" x2="-235.831" y1="-317.466" y2="-317.537" gradientTransform="matrix(78.099 0 0 -32.624 18447.361 -10353.553)" gradientUnits="userSpaceOnUse"><stop offset="0" class="q91zgcc_y"/><stop offset=".44" class="l9c3zxbog"/><stop offset=".99" class="wqwfuj05f"/><stop offset="1" class="wqwfuj05f"/></linearGradient><radialGradient id="SVGfvaUndTF" cx="-235.882" cy="-312.543" r=".076" gradientTransform="matrix(93.113 0 0 -48.655 21986.073 -15193.61)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ezidwnbja"/><stop offset=".99" class="m0lf0xtnz"/><stop offset="1" class="m0lf0xtnz"/></radialGradient><radialGradient id="SVGv1rGLeXK" cx="-235.282" cy="-309.704" r=".097" gradientTransform="matrix(97.434 0 0 -75.848 22937.057 -23467.84)" gradientUnits="userSpaceOnUse"><stop offset="0" class="d1bgm_xyy"/><stop offset=".99" class="r70gc76fy"/><stop offset="1" class="r70gc76fy"/></radialGradient></defs><path fill="url(#SVGiqgdicjk)" class="lt1sqqwjr"/><path fill="url(#SVGF9aq9cWt)" class="t5y3ucb6k"/><path fill="url(#SVG0HSePCnb)" class="qftbqvn2s"/><path fill="url(#SVGvb2glb6k)" class="l17u0--9z"/><path fill="url(#SVG6loDUcxZ)" class="k_-y3gbvg"/><path fill="url(#SVG6FPKXbvK)" class="r7voj5b2c"/><path fill="url(#SVGLCWrsbYP)" class="r268zacrv"/><path fill="url(#SVGf5jZBbJL)" class="cx6hc2bqq"/><path class="jjmk3hqpq"/><path fill="url(#SVGQfUwFbKt)" class="w8y506y2t"/><path fill="url(#SVGSsKSoh4f)" class="xw4nsdb1n"/><path fill="url(#SVG9U0cHUGc)" class="qpqb8bc4w"/><path fill="url(#SVGdb3on5po)" class="i0v0kxdvp"/><path class="al6-_fbtm"/><path fill="url(#SVGfvaUndTF)" class="jqh96abji"/><path fill="url(#SVGv1rGLeXK)" class="y7en-9j8v"/><path fill="url(#SVGkA2IRbug)" class="tcn_g-btq"/><path fill="url(#SVGLvLZ24gI)" class="h8u6ak2_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ruby" /></template>
<style>
.al6-_fbtm {
  fill: var(--svg-color--9e1209, #9e1209);
  d: path("M2 24.332c.153 5.49 4.114 5.572 5.8 5.62l-3.9-9.1z");
}

.anp5c3pdg {
  stop-color: var(--svg-color--900, #900);
}

.cqcs1lp7p {
  stop-color: var(--svg-color--990c00, #990c00);
}

.cx6hc2bqq {
  d: path("m2 24.38l2-3.642L2.382 16.4Z");
}

.d1bgm_xyy {
  stop-color: var(--svg-color--a30c00, #a30c00);
}

.ddk317bha {
  stop-color: var(--svg-color--b31301, #b31301);
}

.dpr9tb3ch {
  stop-color: var(--svg-color--e46342, #e46342);
}

.dtgi8tbtl {
  stop-color: var(--svg-color--9e100a, #9e100a);
}

.ezidwnbja {
  stop-color: var(--svg-color--a80d00, #a80d00);
}

.f4ld04byb {
  stop-color: var(--svg-color--e82609, #e82609);
}

.gk6kz_ald {
  stop-color: var(--svg-color--820c01, #820c01);
}

.h3xd-3bzt {
  stop-color: var(--svg-color--79130d, #79130d);
}

.h8fnprbnu {
  stop-color: var(--svg-color--871101, #871101);
}

.h8u6ak2_p {
  d: path("m21.206 4.528l8.58 1.2c-.458-1.94-1.864-3.192-4.261-3.584l-4.319 2.38Z");
}

.i_f-8ebbv {
  stop-color: var(--svg-color--bf0905, #bf0905);
}

.i0v0kxdvp {
  d: path("M29.337 11.139c1.1-3.327 1.357-8.1-3.841-8.985l-4.265 2.355z");
}

.iipf5j-mn {
  stop-color: var(--svg-color--8b2114, #8b2114);
}

.j1y0librw {
  stop-color: var(--svg-color--fb7655, #fb7655);
}

.jjmk3hqpq {
  fill: var(--svg-color--fff, #fff);
  d: path("m2.274 16.263l1.626 4.61l7.062-1.584l8.062-7.489L21.3 4.569l-3.583-2.53l-6.091 2.28C9.706 6.1 5.982 9.635 5.848 9.7s-2.459 4.464-3.574 6.562Z");
}

.jl8pcyvuf {
  stop-color: var(--svg-color--e42b1e, #e42b1e);
}

.jqh96abji {
  d: path("M19.053 11.791c2.49 1.531 7.509 4.6 7.61 4.661a17.6 17.6 0 0 0 2.619-5.343z");
}

.k_-y3gbvg {
  d: path("m21.813 22.7l-3-11.735L10.243 19Z");
}

.kv77ch53o {
  stop-color: var(--svg-color--b3100c, #b3100c);
}

.l17u0--9z {
  d: path("M7.794 29.937L11.05 19.27L3.885 20.8Z");
}

.l9c3zxbog {
  stop-color: var(--svg-color--910f08, #910f08);
}

.lsv7azf7j {
  stop-color: var(--svg-color--c82410, #c82410);
}

.lt1sqqwjr {
  d: path("M23.693 20.469L7.707 29.961l20.7-1.4L30 7.685Z");
}

.m0lf0xtnz {
  stop-color: var(--svg-color--7e0e08, #7e0e08);
}

.oe74w3r0p {
  stop-color: var(--svg-color--7e110b, #7e110b);
}

.oyjo3ex1c {
  stop-color: var(--svg-color--de3b20, #de3b20);
}

.q7xz9abfp {
  stop-color: var(--svg-color--911209, #911209);
}

.q91zgcc_y {
  stop-color: var(--svg-color--b31000, #b31000);
}

.q9tep7byl {
  stop-color: var(--svg-color--e4714e, #e4714e);
}

.qftbqvn2s {
  d: path("M28.464 28.542L15.43 27.519l-7.654 2.415Z");
}

.qpqb8bc4w {
  d: path("m19.038 11.774l2.754 10.91c3.24-3.407 6.149-7.07 7.573-11.6z");
}

.qw5y8xbnh {
  stop-color: var(--svg-color--bf190b, #bf190b);
}

.r268zacrv {
  d: path("m25.53 2.148l-4.767 2.634l-3.007-2.67Z");
}

.r70gc76fy {
  stop-color: var(--svg-color--800e08, #800e08);
}

.r7voj5b2c {
  d: path("m29.32 11.127l-8.1-6.619l-2.257 7.3Z");
}

.s8aw0sl5f {
  stop-color: var(--svg-color--bd0012, #bd0012);
}

.six_5zb0y {
  stop-color: var(--svg-color--8c0c01, #8c0c01);
}

.t5y3ucb6k {
  d: path("m28.44 28.542l-1.779-12.279l-4.846 6.4Z");
}

.tcn_g-btq {
  d: path("m3.887 20.861l-.612 7.287c1.155 1.577 2.743 1.714 4.409 1.591c-1.205-3-3.614-9-3.8-8.878Z");
}

.u0l4xx4ah {
  stop-color: var(--svg-color--a80d0e, #a80d0e);
}

.ug4qrab9a {
  stop-color: var(--svg-color--c82f1c, #c82f1c);
}

.v4700dkua {
  stop-color: var(--svg-color--9e120b, #9e120b);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.veuf6qxqw {
  stop-color: var(--svg-color--9e0c00, #9e0c00);
}

.vgglilblh {
  stop-color: var(--svg-color--be1a0d, #be1a0d);
}

.w_afh7bgq {
  stop-color: var(--svg-color--c81f11, #c81f11);
}

.w8ttm0bgd {
  stop-color: var(--svg-color--de4024, #de4024);
}

.w8y506y2t {
  d: path("M7.981 7.981C12.14 3.858 17.5 1.421 19.559 3.5s-.124 7.121-4.283 11.244s-9.455 6.69-11.511 4.614s.057-7.258 4.216-11.377");
}

.wqwfuj05f {
  stop-color: var(--svg-color--791c12, #791c12);
}

.wr97chdyu {
  stop-color: var(--svg-color--e57252, #e57252);
}

.wxf-xc86f {
  stop-color: var(--svg-color--a60003, #a60003);
}

.xw4nsdb1n {
  d: path("m7.794 29.933l3.231-10.7l10.729 3.447c-3.879 3.638-8.194 6.713-13.96 7.254Z");
}

.y7en-9j8v {
  d: path("m11.021 19.232l4.319 8.332a28 28 0 0 0 6.385-4.88l-10.7-3.452Z");
}

.yjb2dqbqe {
  stop-color: var(--svg-color--a31601, #a31601);
}

</style>
