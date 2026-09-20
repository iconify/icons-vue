<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVG1Oo86cCx)" class="x-qgllvwc"/><path class="ijfihlbyl"/><path fill="url(#SVGHdlBzXVH)" class="dbu7_wgcv"/><path fill="url(#SVG6FmKneAo)" class="v553jn5wd"/><path fill="url(#SVGd4yrhdcX)" class="w40dqw_5r"/><path fill="url(#SVGU1ws0bwU)" class="ubwfrqbsb"/><path fill="url(#SVGAOO5rb6N)" class="iidgbfbzw"/><path fill="url(#SVGvlP97dit)" class="zz-stabiy"/><path fill="url(#SVGYkl94F9i)" class="xsy4h4d-l"/><path fill="url(#SVGcbijObIu)" class="kysxyl94o"/><path fill="url(#SVG3XZvgbKm)" class="mfue-6bsf"/><path fill="url(#SVGSGOWh9ZR)" class="lpn_66b2g"/><path fill="url(#SVG4WqdCbvB)" class="r4rakic6x"/><path fill="url(#SVGsKQOcdIe)" class="mg-31nbde"/><path class="mmdxonzrn"/><path fill="url(#SVGy3IFmbtQ)" class="q1964v3il"/><path fill="url(#SVGZeUYvbzz)" class="e4vp2_n-h"/><path fill="url(#SVGhhAgQGVh)" class="qvja69bjb"/></g><defs><linearGradient id="SVG1Oo86cCx" x1="12.001" x2="16.42" y1="11.648" y2="8.218" gradientUnits="userSpaceOnUse"><stop class="w09pl-bqo"/><stop offset="1" class="ip0ngccya"/></linearGradient><linearGradient id="SVGHdlBzXVH" x1="11.751" x2="17.418" y1="10.213" y2="17.13" gradientUnits="userSpaceOnUse"><stop class="b8rop1bve"/><stop offset="1" class="f2lxo0v8q"/></linearGradient><linearGradient id="SVG6FmKneAo" x1="12.422" x2="8.097" y1="13.101" y2="16.254" gradientUnits="userSpaceOnUse"><stop class="k3qhy-b0p"/><stop offset="1" class="s50tmz3go"/></linearGradient><linearGradient id="SVGd4yrhdcX" x1="13.717" x2="11.977" y1="11.097" y2="7.32" gradientUnits="userSpaceOnUse"><stop class="yyspbo0js"/><stop offset="1" class="gt_0w4bgz"/></linearGradient><linearGradient id="SVGU1ws0bwU" x1="12.992" x2="15.617" y1="10.859" y2="3.521" gradientUnits="userSpaceOnUse"><stop class="pz8osybzb"/><stop offset="1" class="mhzez0ymk"/></linearGradient><linearGradient id="SVGAOO5rb6N" x1="15.362" x2="12.317" y1="11.762" y2="14.43" gradientUnits="userSpaceOnUse"><stop class="ne7tbtpgb"/><stop offset="1" class="nz401ub3w"/></linearGradient><linearGradient id="SVGvlP97dit" x1="12.726" x2="11.201" y1="11.378" y2="13.937" gradientUnits="userSpaceOnUse"><stop class="l53bstutc"/><stop offset="1" class="ywpul_b7i"/></linearGradient><linearGradient id="SVGYkl94F9i" x1="13.886" x2="11.337" y1="9.475" y2="14.095" gradientUnits="userSpaceOnUse"><stop class="uun36chmi"/><stop offset="1" class="fsqsw3sun"/></linearGradient><linearGradient id="SVGcbijObIu" x1="13.817" x2="10.888" y1="11.307" y2="16.386" gradientUnits="userSpaceOnUse"><stop class="nz401ub3w"/><stop offset="1" class="mueq9mbtq"/></linearGradient><linearGradient id="SVG3XZvgbKm" x1="13.795" x2="8.085" y1="4.914" y2="10.837" gradientUnits="userSpaceOnUse"><stop class="sqeir4bkd"/><stop offset="1" class="a5wymhb4q"/></linearGradient><linearGradient id="SVGSGOWh9ZR" x1="12.793" x2="7.259" y1="10.465" y2="16.761" gradientUnits="userSpaceOnUse"><stop class="fkg-kybup"/><stop offset="1" class="vfq5u_bct"/></linearGradient><linearGradient id="SVG4WqdCbvB" x1="11.222" x2="15.025" y1="7.861" y2="12.467" gradientUnits="userSpaceOnUse"><stop class="kn6u9s9dr"/><stop offset="1" class="b8rop1bve"/></linearGradient><linearGradient id="SVGsKQOcdIe" x1="14.567" x2="11.687" y1="12.405" y2="9.488" gradientUnits="userSpaceOnUse"><stop class="tv94cubcg"/><stop offset=".995" class="touv-lmmf"/></linearGradient><linearGradient id="SVGy3IFmbtQ" x1="17.225" x2="11.384" y1="12.341" y2="8.677" gradientUnits="userSpaceOnUse"><stop class="t1hdl8o-y"/><stop offset="1" class="cu8te_b2r"/></linearGradient><linearGradient id="SVGZeUYvbzz" x1="5.929" x2="18.512" y1="9.655" y2="9.655" gradientUnits="userSpaceOnUse"><stop class="hvner7ycr"/><stop offset="1" class="nukq4fbmq"/></linearGradient><linearGradient id="SVGhhAgQGVh" x1="12.926" x2="11.092" y1="16.728" y2="16.728" gradientUnits="userSpaceOnUse"><stop class="t7pjgmbbi"/><stop offset="1" class="xn5dksb-u"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:flex-background" /></template>
<style>
.a5wymhb4q {
  stop-color: var(--svg-color--1c1c1c, #1c1c1c);
}

.b8rop1bve {
  stop-color: var(--svg-color--dadada, #dadada);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.cu8te_b2r {
  stop-color: var(--svg-color--575757, #575757);
}

.dbu7_wgcv {
  d: path("M19.88 10.613q-.12-.689-.359-1.346L12.015 12H20q-.002-.71-.12-1.387");
}

.e4vp2_n-h {
  d: path("M12.015 4H12q-.704 0-1.375.118L12.015 12l1.39-7.877A8 8 0 0 0 12.014 4");
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

.iidgbfbzw {
  d: path("M8.01 5.064A8 8 0 0 0 5.879 6.85L12.015 12z");
}

.ijfihlbyl {
  fill: var(--svg-color--dadada, #dadada);
  d: path("M18.933 8.007a8 8 0 0 0-.799-1.141L12.014 12l7.507-2.733a8 8 0 0 0-.588-1.261");
}

.ip0ngccya {
  stop-color: var(--svg-color--bdbdbd, #bdbdbd);
}

.k3qhy-b0p {
  stop-color: var(--svg-color--373737, #373737);
}

.kn6u9s9dr {
  stop-color: var(--svg-color--c2c2c2, #c2c2c2);
}

.kysxyl94o {
  d: path("M5.878 6.85a8 8 0 0 0-1.395 2.408L12.016 12z");
}

.l53bstutc {
  stop-color: var(--svg-color--282828, #282828);
}

.lpn_66b2g {
  d: path("M4.483 9.258A8 8 0 0 0 4 12h8.015z");
}

.mfue-6bsf {
  d: path("m12.015 12l7.506 2.732A8 8 0 0 0 20 12z");
}

.mg-31nbde {
  d: path("M5.878 17.15a8 8 0 0 0 2.133 1.786L12.015 12z");
}

.mhzez0ymk {
  stop-color: var(--svg-color--7f7f7f, #7f7f7f);
}

.mmdxonzrn {
  fill: var(--svg-color--c2c2c2, #c2c2c2);
  d: path("M14.75 4.486a8 8 0 0 0-1.346-.362L12.014 12l3.997-6.922a8 8 0 0 0-1.261-.592");
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

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.pz8osybzb {
  stop-color: var(--svg-color--747474, #747474);
}

.q1964v3il {
  d: path("M8.01 18.936a7.9 7.9 0 0 0 2.615.946L12.015 12z");
}

.qvja69bjb {
  d: path("m12.015 12l-1.39 7.882q.671.117 1.375.118h.015q.7 0 1.39-.123z");
}

.r4rakic6x {
  d: path("M17.15 5.878a8 8 0 0 0-1.139-.801l-3.996 6.922l6.12-5.135a8 8 0 0 0-.984-.986");
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

.touv-lmmf {
  stop-color: var(--svg-color--6b6b6b, #6b6b6b);
}

.tv94cubcg {
  stop-color: var(--svg-color--515151, #515151);
}

.ubwfrqbsb {
  d: path("M4 12c0 .935.164 1.863.482 2.742L12.015 12z");
}

.uun36chmi {
  stop-color: var(--svg-color--1a1a1a, #1a1a1a);
}

.v553jn5wd {
  d: path("m12.015 12l1.389 7.877a8 8 0 0 0 2.608-.954z");
}

.vfq5u_bct {
  stop-color: var(--svg-color--7b7b7b, #7b7b7b);
}

.w09pl-bqo {
  stop-color: var(--svg-color--acacac, #acacac);
}

.w40dqw_5r {
  d: path("M4.482 14.742c.32.878.793 1.693 1.395 2.408L12.015 12z");
}

.x-qgllvwc {
  d: path("M10.625 4.119a7.9 7.9 0 0 0-2.615.946l4.005 6.936z");
}

.xn5dksb-u {
  stop-color: var(--svg-color--464646, #464646);
}

.xsy4h4d-l {
  d: path("m12.015 12l6.12 5.135a8 8 0 0 0 1.386-2.403z");
}

.ywpul_b7i {
  stop-color: var(--svg-color--383838, #383838);
}

.yyspbo0js {
  stop-color: var(--svg-color--686868, #686868);
}

.zz-stabiy {
  d: path("m12.015 12l3.997 6.922a8 8 0 0 0 2.122-1.787z");
}

</style>
