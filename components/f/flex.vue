<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGzhlcne0g)" class="rmylmacek"/><path class="xfcimwb4k"/><path fill="url(#SVGYBAiecJl)" class="rqla2ebcq"/><path fill="url(#SVG92LS9bgH)" class="mk3ekiw3v"/><path fill="url(#SVGkdKnhc5V)" class="dqx8u4bcm"/><path fill="url(#SVG0cfdhcAb)" class="to56m3w_b"/><path fill="url(#SVG25ylEcMd)" class="v64j19bod"/><path fill="url(#SVGwZNj6bUu)" class="oqywqmb5f"/><path fill="url(#SVGkgqYebiT)" class="mpp0lcbri"/><path fill="url(#SVGyjcCWdZI)" class="eya0zjbeo"/><path fill="url(#SVGS2qg5Qev)" class="ja7yhhizb"/><path fill="url(#SVGPr9Ngb4g)" class="c-ttk4bjj"/><path fill="url(#SVGwcqLLdhH)" class="a286e-blo"/><path fill="url(#SVGTO3l9bDv)" class="v__jb6b1l"/><path class="m7vnhpq0c"/><path fill="url(#SVGoqQojdFt)" class="jbno6rfzr"/><path fill="url(#SVGNBlYbbSp)" class="ll_pilbwf"/><path fill="url(#SVGvGsyaeAI)" class="yc2i7-gwf"/><defs><linearGradient id="SVGzhlcne0g" x1="12.001" x2="16.973" y1="11.604" y2="7.745" gradientUnits="userSpaceOnUse"><stop class="w09pl-bqo"/><stop offset="1" class="ip0ngccya"/></linearGradient><linearGradient id="SVGYBAiecJl" x1="11.72" x2="18.095" y1="9.99" y2="17.771" gradientUnits="userSpaceOnUse"><stop class="b8rop1bve"/><stop offset="1" class="f2lxo0v8q"/></linearGradient><linearGradient id="SVG92LS9bgH" x1="12.475" x2="7.609" y1="13.239" y2="16.786" gradientUnits="userSpaceOnUse"><stop class="k3qhy-b0p"/><stop offset="1" class="s50tmz3go"/></linearGradient><linearGradient id="SVGkdKnhc5V" x1="13.931" x2="11.975" y1="10.984" y2="6.735" gradientUnits="userSpaceOnUse"><stop class="yyspbo0js"/><stop offset="1" class="gt_0w4bgz"/></linearGradient><linearGradient id="SVG0cfdhcAb" x1="13.117" x2="16.069" y1="10.717" y2="2.462" gradientUnits="userSpaceOnUse"><stop class="pz8osybzb"/><stop offset="1" class="mhzez0ymk"/></linearGradient><linearGradient id="SVG25ylEcMd" x1="15.783" x2="12.357" y1="11.733" y2="14.733" gradientUnits="userSpaceOnUse"><stop class="ne7tbtpgb"/><stop offset="1" class="nz401ub3w"/></linearGradient><linearGradient id="SVGwZNj6bUu" x1="12.817" x2="11.101" y1="11.3" y2="14.179" gradientUnits="userSpaceOnUse"><stop class="l53bstutc"/><stop offset="1" class="ywpul_b7i"/></linearGradient><linearGradient id="SVGkgqYebiT" x1="14.122" x2="11.254" y1="9.159" y2="14.357" gradientUnits="userSpaceOnUse"><stop class="uun36chmi"/><stop offset="1" class="fsqsw3sun"/></linearGradient><linearGradient id="SVGyjcCWdZI" x1="14.044" x2="10.749" y1="11.22" y2="16.934" gradientUnits="userSpaceOnUse"><stop class="nz401ub3w"/><stop offset="1" class="mueq9mbtq"/></linearGradient><linearGradient id="SVGS2qg5Qev" x1="14.019" x2="7.595" y1="4.028" y2="10.692" gradientUnits="userSpaceOnUse"><stop class="sqeir4bkd"/><stop offset="1" class="a5wymhb4q"/></linearGradient><linearGradient id="SVGPr9Ngb4g" x1="12.892" x2="6.666" y1="10.273" y2="17.356" gradientUnits="userSpaceOnUse"><stop class="fkg-kybup"/><stop offset="1" class="vfq5u_bct"/></linearGradient><linearGradient id="SVGwcqLLdhH" x1="11.125" x2="15.404" y1="7.344" y2="12.525" gradientUnits="userSpaceOnUse"><stop class="kn6u9s9dr"/><stop offset="1" class="b8rop1bve"/></linearGradient><linearGradient id="SVGTO3l9bDv" x1="14.888" x2="11.648" y1="12.456" y2="9.174" gradientUnits="userSpaceOnUse"><stop class="tv94cubcg"/><stop offset=".995" class="touv-lmmf"/></linearGradient><linearGradient id="SVGoqQojdFt" x1="17.878" x2="11.307" y1="12.384" y2="8.262" gradientUnits="userSpaceOnUse"><stop class="t1hdl8o-y"/><stop offset="1" class="cu8te_b2r"/></linearGradient><linearGradient id="SVGNBlYbbSp" x1="5.17" x2="19.326" y1="9.362" y2="9.362" gradientUnits="userSpaceOnUse"><stop class="hvner7ycr"/><stop offset="1" class="nukq4fbmq"/></linearGradient><linearGradient id="SVGvGsyaeAI" x1="13.041" x2="10.979" y1="17.319" y2="17.319" gradientUnits="userSpaceOnUse"><stop class="t7pjgmbbi"/><stop offset="1" class="xn5dksb-u"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:flex" /></template>
<style>
.a286e-blo {
  d: path("M17.795 5.113q-.602-.507-1.283-.902L12.017 12L18.9 6.222a9 9 0 0 0-1.107-1.11");
}

.a5wymhb4q {
  stop-color: var(--svg-color--1c1c1c, #1c1c1c);
}

.b8rop1bve {
  stop-color: var(--svg-color--dadada, #dadada);
}

.c-ttk4bjj {
  d: path("M3.543 8.915A9 9 0 0 0 3 12h9.017z");
}

.cu8te_b2r {
  stop-color: var(--svg-color--575757, #575757);
}

.dqx8u4bcm {
  d: path("M3.542 15.085c.36.988.892 1.904 1.57 2.708L12.017 12z");
}

.eya0zjbeo {
  d: path("M5.113 6.206a9 9 0 0 0-1.57 2.709l8.475 3.084z");
}

.f2lxo0v8q {
  stop-color: var(--svg-color--fbfbfb, #fbfbfb);
}

.fkg-kybup {
  stop-color: var(--svg-color--888, #888);
}

.fsqsw3sun {
  stop-color: var(--svg-color--2d2d2d, #2d2d2d);
}

.ft5dv1b6b {
  fill: none;
}

.gt_0w4bgz {
  stop-color: var(--svg-color--787878, #787878);
}

.hvner7ycr {
  stop-color: var(--svg-color--b9b9b9, #b9b9b9);
}

.ip0ngccya {
  stop-color: var(--svg-color--bdbdbd, #bdbdbd);
}

.ja7yhhizb {
  d: path("m12.017 12l8.444 3.073A9 9 0 0 0 21 12z");
}

.jbno6rfzr {
  d: path("M7.512 19.802c.91.526 1.906.886 2.94 1.065L12.018 12z");
}

.k3qhy-b0p {
  stop-color: var(--svg-color--373737, #373737);
}

.kn6u9s9dr {
  stop-color: var(--svg-color--c2c2c2, #c2c2c2);
}

.l53bstutc {
  stop-color: var(--svg-color--282828, #282828);
}

.ll_pilbwf {
  d: path("M12.017 3H12q-.791 0-1.547.133L12.017 12l1.563-8.862A9 9 0 0 0 12.016 3");
}

.m7vnhpq0c {
  fill: var(--svg-color--c2c2c2, #c2c2c2);
  d: path("M15.093 3.546a9 9 0 0 0-1.514-.407L12.017 12l4.496-7.787a9 9 0 0 0-1.42-.667");
}

.mhzez0ymk {
  stop-color: var(--svg-color--7f7f7f, #7f7f7f);
}

.mk3ekiw3v {
  d: path("m12.017 12l1.562 8.862a9 9 0 0 0 2.934-1.074z");
}

.mpp0lcbri {
  d: path("m12.017 12l6.884 5.777a9 9 0 0 0 1.56-2.704z");
}

.mueq9mbtq {
  stop-color: var(--svg-color--838383, #838383);
}

.ne7tbtpgb {
  stop-color: var(--svg-color--b0b0b0, #b0b0b0);
}

.nukq4fbmq {
  stop-color: var(--svg-color--c1c1c1, #c1c1c1);
}

.nz401ub3w {
  stop-color: var(--svg-color--848484, #848484);
}

.oqywqmb5f {
  d: path("m12.017 12l4.496 7.788a9 9 0 0 0 2.388-2.011z");
}

.pz8osybzb {
  stop-color: var(--svg-color--747474, #747474);
}

.rmylmacek {
  d: path("M10.453 3.134a8.9 8.9 0 0 0-2.941 1.064l4.505 7.803z");
}

.rqla2ebcq {
  d: path("M20.865 10.44a9 9 0 0 0-.404-1.514l-8.444 3.073H21q-.002-.799-.135-1.56");
}

.s50tmz3go {
  stop-color: var(--svg-color--3f3f3f, #3f3f3f);
}

.sqeir4bkd {
  stop-color: var(--svg-color--010101, #010101);
}

.t1hdl8o-y {
  stop-color: var(--svg-color--434343, #434343);
}

.t7pjgmbbi {
  stop-color: var(--svg-color--3d3d3d, #3d3d3d);
}

.to56m3w_b {
  d: path("M3 12c0 1.052.184 2.096.543 3.085L12.017 12z");
}

.touv-lmmf {
  stop-color: var(--svg-color--6b6b6b, #6b6b6b);
}

.tv94cubcg {
  stop-color: var(--svg-color--515151, #515151);
}

.uun36chmi {
  stop-color: var(--svg-color--1a1a1a, #1a1a1a);
}

.v__jb6b1l {
  d: path("M5.112 17.793a9 9 0 0 0 2.4 2.01L12.017 12z");
}

.v64j19bod {
  d: path("M7.512 4.197a9 9 0 0 0-2.4 2.01l6.905 5.792z");
}

.vfq5u_bct {
  stop-color: var(--svg-color--7b7b7b, #7b7b7b);
}

.w09pl-bqo {
  stop-color: var(--svg-color--acacac, #acacac);
}

.xfcimwb4k {
  fill: var(--svg-color--dadada, #dadada);
  d: path("M19.8 7.507a9 9 0 0 0-.9-1.283L12.018 12l8.444-3.074a9 9 0 0 0-.662-1.42");
}

.xn5dksb-u {
  stop-color: var(--svg-color--464646, #464646);
}

.yc2i7-gwf {
  d: path("m12.017 12l-1.564 8.867Q11.208 21 12 21h.017q.788 0 1.563-.138z");
}

.ywpul_b7i {
  stop-color: var(--svg-color--383838, #383838);
}

.yyspbo0js {
  stop-color: var(--svg-color--686868, #686868);
}

</style>
