<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGhSoNvcoQ)" class="blnixhbfm"/><path fill="url(#SVGGyh9teIm)" class="ui__ykflm"/><path class="qmfxa9qux"/><path fill="url(#SVGaJ7q6duk)" class="mlkftxb7u"/><path class="jfxhp1b1v"/><path fill="url(#SVGclcqQt7x)" class="yl-riacda"/><path class="va7rucbyu"/><path class="xudvw0bwo"/><path fill="url(#SVGba1mfesd)" class="f-pfy7b2h"/><path fill="url(#SVGRorfGcXI)" class="hg7-ufbqc"/><path fill="url(#SVGQlmgVdul)" class="cmpwxtbzd"/><path fill="url(#SVGmcK5Id4A)" class="qyhkxlb1g"/><path class="p1c867b_k"/><path fill="url(#SVGjnEYceEY)" class="r1_mrwqor"/><path fill="url(#SVGXoLZYboT)" class="wctl9rbyx"/><path class="yzhh8kb2g"/><path fill="url(#SVGNJmp2cjH)" class="pj-9osbwf"/><path fill="url(#SVGBzNBeb7H)" class="zy4i75zkw"/><path class="cj1gnyxjo"/><path class="ltb3g-bkd"/><path fill="url(#SVGSkvigd5x)" class="a9wg63bxg"/><path class="esud9xb2r"/><path class="qja7epzdy"/><path class="k6x6a1bva"/><path class="jomtgvbus"/><path class="hxpkqo5tv"/><path fill="url(#SVGTyN7Yb8K)" class="i8b2vzbdt"/><path class="gp2ezuxwz"/><path class="dodt84v8e"/><path class="nbnosmisz"/><path fill="url(#SVG9YHUGdDo)" class="ynzg1ebab"/><path fill="url(#SVGez1Fheha)" class="h178xpbsb"/><path fill="url(#SVGXag6Gbiq)" class="w99g7vb4d"/><path fill="url(#SVGOUAk3cBJ)" class="pk0z04cwb"/><path fill="url(#SVGnsoHkc1a)" class="aqimt8b7k"/><path class="mpoej1btn"/><path fill="url(#SVGwW2NpcSb)" class="ob_0x-bhh"/><path class="zxltsebbw"/><defs><linearGradient id="SVGhSoNvcoQ" x1="20.715" x2="2.334" y1="4.117" y2="11.954" gradientUnits="userSpaceOnUse"><stop class="p9azygbpg"/><stop offset=".13" class="gts-a2bll"/><stop offset=".34" class="g0kpxcq9n"/><stop offset=".51" class="ir5d_dw-d"/><stop offset="1" class="c7x8cibnx"/></linearGradient><linearGradient id="SVGGyh9teIm" x1="14.383" x2="7.476" y1="7.907" y2="12.319" gradientUnits="userSpaceOnUse"><stop class="j6xwapbni"/><stop offset=".25" class="n_9gckc2a"/><stop offset=".48" class="sc534obhl"/><stop offset=".78" class="irfq6qzvt"/><stop offset="1" class="hqsoeac0j"/></linearGradient><linearGradient id="SVGaJ7q6duk" x1="8.196" x2="11.69" y1="8.005" y2="17.413" gradientUnits="userSpaceOnUse"><stop class="j6xwapbni"/><stop offset=".25" class="n_9gckc2a"/><stop offset=".48" class="sc534obhl"/><stop offset=".78" class="irfq6qzvt"/><stop offset="1" class="hqsoeac0j"/></linearGradient><linearGradient id="SVGclcqQt7x" x1="10.829" x2="6.504" y1="6.394" y2="12.192" gradientUnits="userSpaceOnUse"><stop class="j6xwapbni"/><stop offset=".25" class="n_9gckc2a"/><stop offset=".48" class="sc534obhl"/><stop offset=".78" class="irfq6qzvt"/><stop offset="1" class="hqsoeac0j"/></linearGradient><linearGradient id="SVGba1mfesd" x1="6.253" x2="22.477" y1="4.907" y2="13.321" gradientUnits="userSpaceOnUse"><stop class="k_26bhbri"/><stop offset=".35" class="x5tpypb8c"/><stop offset=".63" class="tdjiqjc7d"/><stop offset="1" class="d84lftbgx"/></linearGradient><linearGradient id="SVGRorfGcXI" x1="19.754" x2="10.852" y1="3.57" y2="14.546" gradientUnits="userSpaceOnUse"><stop class="d33yvbb6p"/><stop offset=".45" class="at77yrnkw"/><stop offset=".98" class="r3s95mb8n"/></linearGradient><linearGradient id="SVGQlmgVdul" x1="3.893" x2="8.945" y1="4.169" y2="20.759" gradientUnits="userSpaceOnUse"><stop class="zmoj2kbvj"/><stop offset=".13" class="dw4b5sbir"/><stop offset=".34" class="fvp_q9g-e"/><stop offset=".51" class="jib6nyb-u"/><stop offset="1" class="xf93wwt2p"/></linearGradient><linearGradient id="SVGmcK5Id4A" x1="11.879" x2="11.033" y1="4.317" y2="20.638" gradientUnits="userSpaceOnUse"><stop class="wgtwfccct"/><stop offset=".26" class="s82pzd3_v"/><stop offset=".47" class="oebkzccuu"/><stop offset=".66" class="fnzv44qsr"/><stop offset=".98" class="iure3fjhn"/></linearGradient><linearGradient id="SVGjnEYceEY" x1="12.03" x2="12.03" y1="3.592" y2="20.407" gradientUnits="userSpaceOnUse"><stop class="wgtwfccct"/><stop offset=".26" class="s82pzd3_v"/><stop offset=".57" class="oebkzccuu"/><stop offset=".76" class="fnzv44qsr"/><stop offset="1" class="iure3fjhn"/></linearGradient><linearGradient id="SVGXoLZYboT" x1="12" x2="12" y1="3.592" y2="20.407" gradientUnits="userSpaceOnUse"><stop class="j-8gvpbrh"/><stop offset=".32" class="vqabr5quw"/><stop offset="1" class="bfmp7k-xp"/></linearGradient><linearGradient id="SVGNJmp2cjH" x1="4.338" x2="15.599" y1="17.259" y2="7.135" gradientUnits="userSpaceOnUse"><stop class="afr87ubye"/><stop offset=".17" class="oy5zeebpv"/><stop offset=".37" class="c927qmbzh"/><stop offset=".7" class="mrtlx4b8a"/><stop offset="1" class="pvnw0cczo"/></linearGradient><linearGradient id="SVGBzNBeb7H" x1="11.277" x2="15.526" y1="3.754" y2="19.24" gradientUnits="userSpaceOnUse"><stop class="wjwtdjc2i"/><stop offset=".09" class="sqocahbjl"/><stop offset=".22" class="cgs16obza"/><stop offset=".53" class="t2aihyqyn"/><stop offset="1" class="oshsx8u5o"/></linearGradient><linearGradient id="SVGSkvigd5x" x1="5.174" x2="21.158" y1="4.517" y2="6.218" gradientUnits="userSpaceOnUse"><stop class="b8mxppbkz"/><stop offset=".09" class="v9irpjb-f"/><stop offset=".32" class="khg_jbckx"/><stop offset=".55" class="l13cw2bme"/><stop offset=".88" class="zyznwhvzv"/><stop offset="1" class="julpz4b7h"/></linearGradient><linearGradient id="SVGTyN7Yb8K" x1="11.879" x2="11.918" y1="3.595" y2="20.407" gradientUnits="userSpaceOnUse"><stop class="i3jx6crwh"/><stop offset="1" class="pob2u_zli"/></linearGradient><linearGradient id="SVG9YHUGdDo" x1="3" x2="20.294" y1="12" y2="14.341" gradientUnits="userSpaceOnUse"><stop class="ulxvtkpwj"/><stop offset="1" class="q7fw84b7j"/></linearGradient><linearGradient id="SVGez1Fheha" x1="12.024" x2="11.273" y1="3.592" y2="19.768" gradientUnits="userSpaceOnUse"><stop class="ehyjxac6i"/><stop offset=".88" class="ybf_liycz"/><stop offset="1" class="cl0vaewzu"/></linearGradient><linearGradient id="SVGXag6Gbiq" x1="5.173" x2="23.153" y1="4.51" y2="8.743" gradientUnits="userSpaceOnUse"><stop offset=".32" class="f_vic6iji"/><stop offset=".62" class="jl1al0b3h"/><stop offset="1" class="pi253rhbf"/></linearGradient><linearGradient id="SVGOUAk3cBJ" x1="5.542" x2="19.626" y1="4.806" y2="17.043" gradientUnits="userSpaceOnUse"><stop class="sv83-4b_f"/><stop offset=".32" class="isrc1f5vd"/><stop offset=".62" class="ts6tj1b9q"/><stop offset="1" class="qjg8gygsp"/></linearGradient><linearGradient id="SVGnsoHkc1a" x1="5.53" x2="19.55" y1="4.815" y2="17.006" gradientUnits="userSpaceOnUse"><stop class="vz6fch2yu"/><stop offset=".32" class="vzebq9b_s"/><stop offset=".62" class="nnjqm4vcc"/><stop offset="1" class="j90f2tb2j"/></linearGradient><linearGradient id="SVGwW2NpcSb" x1="12" x2="12" y1="3.592" y2="20.408" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".49" class="tl2ewnbhe"/><stop offset="1" class="alt4wly_v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gsts" /></template>
<style>
.a9wg63bxg {
  d: path("M9.287 6.321c-.707.027-1.143.745-1.276 1.096c.244-.447.787-.447 1.117-.447c1.372 0 2.691.958 3.303 1.644c.973.127 1.452.526 1.574.707v-.478l.197-.23c-.34-.132-.495-.334-.527-.425c.628-.122 1.011.059 1.117.165a.76.76 0 0 1 0-.803c-1.015-.229-1.606-.032-2.031 0s-.458.287-.92-.42c-.368-.57-1.852-.771-2.554-.809");
}

.afr87ubye {
  stop-color: var(--svg-color--f68701, #f68701);
}

.alt4wly_v {
  stop-color: var(--svg-color--a8a8a8, #a8a8a8);
}

.aqimt8b7k {
  d: path("M8.405 9.9c-.288-.026-.469.357-.527.548c.142-.077.3-.12.463-.127c.18 0 .377.367.457.548a.37.37 0 0 0 .293-.16c.08-.133.08-.377.069-.484a1.8 1.8 0 0 0-.755-.319z");
}

.at77yrnkw {
  stop-color: var(--svg-color--fdd500, #fdd500);
}

.b8mxppbkz {
  stop-color: var(--svg-color--fb0e2d, #fb0e2d);
}

.bfmp7k-xp {
  stop-color: var(--svg-color--ecb002, #ecb002);
}

.blnixhbfm {
  d: path("M16.457 8.518c-.547.537-2.234 1.644-3.01 2.128l1.41 1.611c.707-.271 2.33-.904 3.143-1.292c.814-.389.82-.915.718-1.128c.32-.282.308-.808.266-1.032a.74.74 0 0 0 .041-.847a.8.8 0 0 0-.206-.217c.144-.223.32-.77-.1-1.16c-.522-.483-1.57 1.256-2.256 1.937z");
}

.c7x8cibnx {
  stop-color: var(--svg-color--7c2204, #7c2204);
}

.c927qmbzh {
  stop-color: var(--svg-color--e64809, #e64809);
}

.cgs16obza {
  stop-color: var(--svg-color--ff9e01, #ff9e01);
}

.cj1gnyxjo {
  fill: var(--svg-color--ce4f2f, #ce4f2f);
  d: path("M6.6 16.474c-.053-.228-.063-1.063-.063-1.446c.404.255 1.702.765 3.67.739c1.962-.027 4.877-1.149 6.09-1.707l.49 1.159c-.83.638-3.245 1.942-6.256 2.096c-3.01.154-3.872-.495-3.93-.84");
}

.cl0vaewzu {
  stop-color: var(--svg-color--be6604, #be6604);
}

.cmpwxtbzd {
  d: path("m5.521 7.193l2.687 4.096l-1.08 1.16c-1.575-.613-2-1.708-2.096-2.224a.64.64 0 0 1 .325-.713a1.45 1.45 0 0 1-.325-.548c-.08-.255.032-.558.096-.675c-.16-.389-.293-1.096-.096-1.32c.16-.18.394.075.49.224");
}

.d33yvbb6p {
  stop-color: var(--svg-color--894e02, #894e02);
}

.d84lftbgx {
  stop-color: var(--svg-color--b78407, #b78407);
}

.dodt84v8e {
  fill: var(--svg-color--ffa200, #ffa200);
  d: path("M13.51 13.64h-1.143c.234.08.468.42.558.586h1.01c-.052-.394-.302-.553-.425-.585m-.228 2.032l-1.011-.063c.106-.144.356-.474.49-.681c.159-.256.425-.32.75-.288c.33.032.494.192.33.48c-.134.233-.426.467-.56.552");
}

.dw4b5sbir {
  stop-color: var(--svg-color--e48801, #e48801);
}

.ehyjxac6i {
  stop-color: var(--svg-color--ffeb0c, #ffeb0c);
}

.esud9xb2r {
  fill: var(--svg-color--fdfa03, #fdfa03);
  d: path("M15.574 10.252h-.49c-.105 0-.34.414-.393 1.292h3.08c.106-.117.266-.638 0-1L18 9.321c.074-.16.106-.49-.362-.516l-1.67-.096zm1.346 1.452h.787l-.197 1.356c-.037-.41-.196-1.25-.59-1.356m-.298-2.288l.82.032l-.128.873l-.92-.032z");
}

.f_vic6iji {
  stop-color: var(--svg-color--ffa302, #ffa302);
}

.f-pfy7b2h {
  d: path("M16.133 19.214c-.053-.175-1.244-.611-1.835-.803l.724-.452c.303.25.968.745 1.175.745c.266 0 .07-.453.394-.426c.33.037.07.65.394.936c.33.293.952.133 1.117.426c.127.229-.298.244-.532.223c.08.043.223.197.17.479c-.053.287-.851-.436-1.245-.835c.01.202-.021.617-.229.643c-.265.032-.069-.707-.133-.936");
}

.fnzv44qsr {
  stop-color: var(--svg-color--e77209, #e77209);
}

.ft5dv1b6b {
  fill: none;
}

.fvp_q9g-e {
  stop-color: var(--svg-color--bd4707, #bd4707);
}

.g0kpxcq9n {
  stop-color: var(--svg-color--b5380a, #b5380a);
}

.gp2ezuxwz {
  fill: var(--svg-color--facd02, #facd02);
  d: path("M12.265 13.48h-.585v2.319h.457c.208.138.665.42.851.42c.23 0 1.474-.293 1.543-1.676c.064-1.383-.984-1.452-1.447-1.484c-.367-.026-.691.266-.819.42");
}

.gts-a2bll {
  stop-color: var(--svg-color--d85a0a, #d85a0a);
}

.h178xpbsb {
  d: path("M14.367 14.576c-.053-1.01-.745-1.26-1.085-1.26c.277.106.835.51.888 1.26c.053.745-.744 1.32-1.149 1.516c.469-.09 1.394-.51 1.346-1.516");
}

.hg7-ufbqc {
  d: path("M6.898 18.283c.107-.287.346-.335.458-.32l.425.16c-.186.053-.585.176-.691.255c-.128.096-.064.32-.064.644c0 .32.07.26.33.516c.266.26.16.388-.133.484s-.718-.707-1.08-1c-.362-.287-.85-.191-1.143-.58c-.298-.388.52-.388.882-.319c.362.064.554.639.75.708c.197.064.133-.197.266-.548");
}

.hqsoeac0j {
  stop-color: var(--svg-color--fbe008, #fbe008);
}

.hxpkqo5tv {
  fill: var(--svg-color--fdfa03, #fdfa03);
  d: path("M17.44 14.252c.134-2.319-.707-2.766-1.143-2.707c-.447.085-1.345.824-1.345 3.096c0 2.835.888 2.898 1.085 2.898c.191 0 1.244-.383 1.404-3.287");
}

.i3jx6crwh {
  stop-color: var(--svg-color--d76701, #d76701);
}

.i8b2vzbdt {
  d: path("M16.34 12.868c-.138.032-.596.361-.59 1.627c0 .809.122 1.187.234 1.362c.053.08.1.117.133.133a.2.2 0 0 0 .074.016c.021-.005.133-.043.266-.25c.144-.234.298-.675.34-1.495c.032-.654-.069-1.01-.18-1.202c-.107-.175-.218-.196-.277-.191m.527.021c.16.266.255.702.223 1.383a3.5 3.5 0 0 1-.388 1.66c-.186.298-.394.393-.51.393c-.038 0-.107 0-.192-.042a.64.64 0 0 1-.266-.25c-.154-.25-.277-.708-.277-1.538c-.01-1.33.484-1.867.83-1.941h.01c.187-.032.41.059.575.335z");
}

.ir5d_dw-d {
  stop-color: var(--svg-color--a83308, #a83308);
}

.irfq6qzvt {
  stop-color: var(--svg-color--ee8e06, #ee8e06);
}

.isrc1f5vd {
  stop-color: var(--svg-color--531200, #531200);
}

.iure3fjhn {
  stop-color: var(--svg-color--fca615, #fca615);
}

.j-8gvpbrh {
  stop-color: var(--svg-color--ffcd02, #ffcd02);
}

.j6xwapbni {
  stop-color: var(--svg-color--ffdf01, #ffdf01);
}

.j90f2tb2j {
  stop-color: var(--svg-color--550601, #550601);
  stop-opacity: 0.4;
}

.jfxhp1b1v {
  fill: var(--svg-color--591c00, #591c00);
  d: path("M20.51 4.012a.287.287 0 0 1-.138-.372c.1.02.266.117.138.372");
}

.jib6nyb-u {
  stop-color: var(--svg-color--9a3809, #9a3809);
}

.jl1al0b3h {
  stop-color: var(--svg-color--ffdb06, #ffdb06);
}

.jomtgvbus {
  fill: var(--svg-color--f98d08, #f98d08);
  d: path("M15.708 11.805h-1.474a.77.77 0 0 0-.425.479h1.542c.101-.155.282-.384.356-.48m-.655.867h-1.441c-.107.16-.362.798-.49 2.063a3.46 3.46 0 0 0 .915 2.644l1.67.064c-.691-.612-.723-1.032-.85-2.191c-.107-.926.085-2.107.196-2.58");
}

.julpz4b7h {
  stop-color: var(--svg-color--e40d2c, #e40d2c);
}

.k_26bhbri {
  stop-color: var(--svg-color--522100, #522100);
}

.k6x6a1bva {
  fill: var(--svg-color--feee05, #feee05);
  d: path("M16.33 11.544h-2.197c-.292.064-.925.713-1.111 2.771c-.181 2.064.58 2.926.983 3.096l1.995.096l.33-5.958z");
}

.khg_jbckx {
  stop-color: var(--svg-color--e30a27, #e30a27);
}

.l13cw2bme {
  stop-color: var(--svg-color--c6061f, #c6061f);
}

.ltb3g-bkd {
  fill: var(--svg-color--9d2b13, #9d2b13);
  d: path("M8.958 16.124a4.45 4.45 0 0 1-2.224-.453v.905c.734.462 1.9.532 2.394.516c.308-.34.016-.788-.165-.968zm1.479.968c-.32-.314-.176-.862-.07-1.101c.708.08 2.787-.373 3.734-.612l.266.968c-.973.49-3.026.697-3.936.745z");
}

.mlkftxb7u {
  d: path("M19.224 3.885c-.155.288 0 .426.095.458l1.208-.282c.154-.303-.048-.436-.165-.468z");
}

.mpoej1btn {
  fill: var(--svg-color--9e260d, #9e260d);
  d: path("M11.122 10.092c.831 0 1.505-.779 1.505-1.74c0-.96-.674-1.739-1.505-1.739s-1.505.779-1.505 1.74c0 .96.674 1.739 1.505 1.739");
}

.mrtlx4b8a {
  stop-color: var(--svg-color--e84608, #e84608);
}

.n_9gckc2a {
  stop-color: var(--svg-color--e88f02, #e88f02);
}

.nbnosmisz {
  fill: var(--svg-color--ffd304, #ffd304);
  d: path("M11.65 15.831c.613 0 1.111-.533 1.111-1.191s-.498-1.192-1.112-1.192s-1.111.534-1.111 1.192s.497 1.191 1.111 1.191");
}

.nnjqm4vcc {
  stop-color: var(--svg-color--900b0c, #900b0c);
}

.ob_0x-bhh {
  d: path("M11.09 9.71c.74 0 1.34-.665 1.34-1.485s-.6-1.484-1.34-1.484s-1.34.665-1.34 1.484c0 .82.6 1.484 1.34 1.484");
}

.oebkzccuu {
  stop-color: var(--svg-color--ffe309, #ffe309);
}

.oshsx8u5o {
  stop-color: var(--svg-color--ffb93d, #ffb93d);
}

.oy5zeebpv {
  stop-color: var(--svg-color--ef6205, #ef6205);
}

.p1c867b_k {
  fill: var(--svg-color--fad502, #fad502);
  d: path("M6.111 12.768c.394-1.133 1.101-1.224 1.41-1.128l-.755 1.42zm.655 3.547c-.655-.234-.974-.936-1.048-1.255l.984-.16z");
}

.p9azygbpg {
  stop-color: var(--svg-color--ef8807, #ef8807);
}

.pi253rhbf {
  stop-color: var(--svg-color--a92c0e, #a92c0e);
}

.pj-9osbwf {
  d: path("M17.967 11.773c.128 1.17.07 3.883-1.212 5.383c-1.607 1.867-5.075 1.93-5.57 1.899c-.489-.032-4.19-.016-4.712-4.027a4.4 4.4 0 0 1 .053-1.468a.6.6 0 0 1-.383-.016c.197-.293 1.606-2.745 1.702-3.287c.101-.548-.16-1.84.165-2.803A1.61 1.61 0 0 1 9.32 6.39c-.043-.154 0-.527.526-.809c.521-.282.851-.117.947 0l.07.585a.75.75 0 0 1 .685-.069v.516c.181.107.362.862.426 1.224a3.91 3.91 0 0 0 2.718 2.611h-.628c1.505.702 3.112 1.373 3.904 1.325");
}

.pk0z04cwb {
  d: path("M8.894 8.39c-.107-.388-.521-.51-.718-.52l.16 3.286c.132.027.473.23.627.325c.495-.053.404-.862.293-1.255q-.152-.928-.362-1.84z");
}

.pob2u_zli {
  stop-color: var(--svg-color--7c0e07, #7c0e07);
}

.pvnw0cczo {
  stop-color: var(--svg-color--ee5205, #ee5205);
}

.q7fw84b7j {
  stop-color: var(--svg-color--230100, #230100);
}

.qja7epzdy {
  fill: var(--svg-color--e89200, #e89200);
  d: path("m16.425 8.838l-.388-.032l-.33 1.383h.558zm-1.207 2.58h-.394c0-.261.053-.937.26-.937c.214 0 .176.676.134.936m.26 0c.107-.31.043-.81 0-.937l2.23.128c.233.26.095.702 0 .808h-2.235z");
}

.qjg8gygsp {
  stop-color: var(--svg-color--000205, #000205);
}

.qmfxa9qux {
  fill: var(--svg-color--591c00, #591c00);
  d: path("M15.281 6.13a.414.414 0 0 1 .49-.288c0 .139-.096.389-.49.287");
}

.qyhkxlb1g {
  d: path("m6.08 13.06l-2.554-.254V14.8l2.288.23c.164-.198.494-.671.494-1.033s-.154-.776-.228-.936");
}

.r1_mrwqor {
  d: path("m6.67 12.735l-1.117.101c.133.128.415.527.495 1.096c.074.564-.34 1.053-.559 1.224l.883.191c.654-.479.623-.867.654-1.415a2.13 2.13 0 0 0-.356-1.197");
}

.r3s95mb8n {
  stop-color: var(--svg-color--bb7402, #bb7402);
}

.s82pzd3_v {
  stop-color: var(--svg-color--ec8a01, #ec8a01);
}

.sc534obhl {
  stop-color: var(--svg-color--ffe103, #ffe103);
}

.sqocahbjl {
  stop-color: var(--svg-color--f24b13, #f24b13);
}

.sv83-4b_f {
  stop-color: var(--svg-color--853301, #853301);
}

.t2aihyqyn {
  stop-color: var(--svg-color--ff9602, #ff9602);
}

.tdjiqjc7d {
  stop-color: var(--svg-color--ffd50a, #ffd50a);
}

.tl2ewnbhe {
  stop-color: var(--svg-color--dbd9da, #dbd9da);
}

.ts6tj1b9q {
  stop-color: var(--svg-color--010000, #010000);
}

.ui__ykflm {
  d: path("M15.117 4.326c-.447-.128-.601.117-.622.255l.723 1.58c.468.128.612-.181.622-.351l-.723-1.49z");
}

.ulxvtkpwj {
  stop-color: var(--svg-color--933905, #933905);
}

.v9irpjb-f {
  stop-color: var(--svg-color--fe2e4e, #fe2e4e);
}

.va7rucbyu {
  fill: var(--svg-color--591c00, #591c00);
  d: path("M20.824 9.513a.21.21 0 0 1 .052-.232a.2.2 0 0 1 .07-.045c.043.064.08.202-.122.277");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vqabr5quw {
  stop-color: var(--svg-color--ffd108, #ffd108);
}

.vz6fch2yu {
  stop-color: var(--svg-color--ff7887, #ff7887);
}

.vzebq9b_s {
  stop-color: var(--svg-color--c52726, #c52726);
}

.w99g7vb4d {
  d: path("M8.729 7.29c-.362 0-.564.318-.617.483a.24.24 0 0 1 .064.16c.021 1.032.053 3.117.032 3.191c-.027.08-.16.053-.229.032c.117.207.457.617.851.617s.692-.356.692-.548l-.17-3.324c0-.415-.389-.612-.623-.612");
}

.wctl9rbyx {
  d: path("M3.49 14.8c.27 0 .489-.463.489-1.033s-.22-1.032-.49-1.032S3 13.197 3 13.767s.22 1.032.49 1.032");
}

.wgtwfccct {
  stop-color: var(--svg-color--fdde06, #fdde06);
}

.wjwtdjc2i {
  stop-color: var(--svg-color--fe5b16, #fe5b16);
}

.x5tpypb8c {
  stop-color: var(--svg-color--fed308, #fed308);
}

.xf93wwt2p {
  stop-color: var(--svg-color--c53d09, #c53d09);
}

.xudvw0bwo {
  fill: var(--svg-color--b20c0c, #b20c0c);
  d: path("M7.292 18.055c-.16-.335.346-.526.623-.58l.914.713c-.446.096-1.383.202-1.542-.133z");
}

.ybf_liycz {
  stop-color: var(--svg-color--ca9307, #ca9307);
}

.yl-riacda {
  d: path("M20.181 8.783c-.234.085-.223.24-.186.303l.814.463c.244-.09.202-.266.154-.346z");
}

.ynzg1ebab {
  d: path("M11.611 15.188c.27 0 .49-.26.49-.58s-.22-.58-.49-.58s-.489.26-.489.58s.22.58.49.58");
}

.yzhh8kb2g {
  fill: var(--svg-color--751509, #751509);
  d: path("M3.489 14.347c.126 0 .229-.26.229-.58s-.103-.58-.229-.58s-.229.26-.229.58s.103.58.229.58");
}

.zmoj2kbvj {
  stop-color: var(--svg-color--fff505, #fff505);
}

.zxltsebbw {
  fill: var(--svg-color--0c0e0d, #0c0e0d);
  d: path("M11.484 7.97a.423.423 0 0 0 .425-.42a.423.423 0 0 0-.425-.421a.423.423 0 0 0-.426.42c0 .232.19.42.426.42");
}

.zy4i75zkw {
  d: path("M9.845 5.55c.521-.282.851-.117.947 0l.07.585a.74.74 0 0 1 .685-.069v.516c.181.106.362.862.426 1.223a3.91 3.91 0 0 0 2.718 2.612h-1.213l.692 1.165l-1.245-.096v1.58l-1.968-.968l-.585 2.287l-2-1.612l-1.08 1.389l-.33-1.096c-.18.543-.622.526-.819.452c.197-.293 1.606-2.745 1.702-3.287c.101-.548-.16-1.84.165-2.809A1.61 1.61 0 0 1 9.32 6.36c-.043-.15 0-.522.526-.804z");
}

.zyznwhvzv {
  stop-color: var(--svg-color--ff314d, #ff314d);
}

</style>
