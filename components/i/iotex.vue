<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGzaJaedmW" width="5" height="5" x="13" y="3" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="o-r6murll"/></mask><mask id="SVG1RueJcBp" width="4" height="5" x="17" y="5" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="re_q95hyp"/></mask><mask id="SVGDszTpbrR" width="5" height="5" x="13" y="7" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="gmxjtgq4i"/></mask><mask id="SVGjabuScMj" width="4" height="5" x="17" y="9" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="xku2qgb8f"/></mask><mask id="SVGbk8l132F" width="5" height="5" x="13" y="11" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="z-l8rjstb"/></mask><mask id="SVGDDCwZSDj" width="4" height="5" x="17" y="13" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="d2gh1pbzj"/></mask><mask id="SVG1O8tycns" width="5" height="6" x="4" y="6" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="a_frm8upk"/></mask><mask id="SVGk0LtBdAR" width="4" height="5" x="9" y="8" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="ogm0lxbfr"/></mask><mask id="SVGuwvOZciC" width="5" height="5" x="6" y="11" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="jz7yllb-d"/></mask><mask id="SVGNjyf6bDi" width="5" height="5" x="8" y="14" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="xqtzposzh"/></mask><mask id="SVGzRP7DbhZ" width="5" height="6" x="13" y="15" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="ark4p6bjb"/></mask><mask id="SVGrwqzJdJa" width="5" height="5" x="9" y="6" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="x8jrj_d1z"/></mask><mask id="SVGKRAOedQZ" width="4" height="5" x="10" y="3" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="ucz_ddius"/></mask><mask id="SVGgehtTfmC" width="4" height="5" x="6" y="4" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="ks-dfob9g"/></mask><mask id="SVGNZ2TpbUx" width="5" height="5" x="9" y="6" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="zdka_zfyd"/></mask><mask id="SVG5QXPBHkJ" width="5" height="5" x="5" y="8" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="lp7e7mbfo"/></mask><mask id="SVG9F8OMaEc" width="4" height="5" x="10" y="11" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="lat_v3ylf"/></mask><mask id="SVGp78HteWL" width="4" height="5" x="3" y="12" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="pp34-cb6f"/></mask><mask id="SVGbufY2dFx" width="4" height="5" x="17" y="7" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="iu4hdvcyy"/></mask><mask id="SVG588Ycuyk" width="5" height="5" x="13" y="9" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="j6g8vrbyt"/></mask><mask id="SVGMGNvRdPt" width="4" height="5" x="17" y="11" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="a22zxxb9z"/></mask><mask id="SVGoyzgWdYG" width="5" height="5" x="13" y="13" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="u0aiu9ylc"/></mask><mask id="SVG7WjrHc7h" width="5" height="6" x="9" y="14" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="pis3_wbau"/></mask><mask id="SVGzIqS0bzh" width="5" height="5" x="13" y="5" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="b16nclbgt"/></mask><g class="ft5dv1b6b"><g mask="url(#SVGzaJaedmW)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVG1RueJcBp)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGDszTpbrR)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGjabuScMj)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGbk8l132F)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGDDCwZSDj)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVG1O8tycns)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGk0LtBdAR)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGuwvOZciC)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGNjyf6bDi)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGzRP7DbhZ)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGrwqzJdJa)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGKRAOedQZ)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGgehtTfmC)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGNZ2TpbUx)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVG5QXPBHkJ)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVG9F8OMaEc)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGp78HteWL)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGbufY2dFx)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVG588Ycuyk)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGMGNvRdPt)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGoyzgWdYG)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVG7WjrHc7h)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><g mask="url(#SVGzIqS0bzh)"><path fill="url(#SVGlOHLIdrl)" class="m0-jxf1hs"/></g><defs><linearGradient id="SVGlOHLIdrl" x1="5.252" x2="28.003" y1="12.971" y2="16.854" gradientUnits="userSpaceOnUse"><stop offset=".07" class="i5zzcz8in"/><stop offset=".369" class="erxb15e0q"/><stop offset="1" class="wjyp-zbjo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:iotex" /></template>
<style>
.a_frm8upk {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.704 6.96v4.097l3.554-2.052z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.a22zxxb9z {
  fill: var(--svg-color--fff, #fff);
  d: path("M21 11.195v4.098l-3.555-2.046z");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.ark4p6bjb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.863 15.93v4.097l3.548-2.052z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.b16nclbgt {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.446 5.052v4.097L13.89 7.098z");
}

.d2gh1pbzj {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.446 13.246v4.098L21 15.292z");
}

.erxb15e0q {
  stop-color: var(--svg-color--72a7ff, #72a7ff);
}

.ft5dv1b6b {
  fill: none;
}

.gmxjtgq4i {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.892 7.097v4.098l3.554-2.046z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.i5zzcz8in {
  stop-color: var(--svg-color--77fe9e, #77fe9e);
}

.iu4hdvcyy {
  fill: var(--svg-color--fff, #fff);
  d: path("M21 7.097v4.098l-3.555-2.046z");
}

.j6g8vrbyt {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.446 9.15v4.097l-3.555-2.052z");
  opacity: var(--svg-opacity--0-95, 0.95);
}

.jz7yllb-d {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.554 11.075v4.097l3.554-2.052z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ks-dfob9g {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.781 4.741v4.097L6.227 6.787z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.lat_v3ylf {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.892 11.195v4.098l-3.549-2.046z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.lp7e7mbfo {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.173 8.483v4.097l-3.555-2.046z");
  opacity: var(--svg-opacity--0-95, 0.95);
}

.m0-jxf1hs {
  d: path("M22.095 2.045H2.726v19.09h19.369z");
}

.o-r6murll {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.892 3v4.098l3.554-2.046z");
}

.ogm0lxbfr {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.19 8.483v4.097l3.548-2.046z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pis3_wbau {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.105 14.954v4.097l-3.554-2.046z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.pp34-cb6f {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.554 12.15v4.097L3 14.195z");
  opacity: var(--svg-opacity--0-55, 0.55);
}

.re_q95hyp {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.446 5.052v4.097L21 7.098z");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.u0aiu9ylc {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.446 13.246v4.098l-3.555-2.052z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.ucz_ddius {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.892 3v4.098l-3.555-2.046z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.wjyp-zbjo {
  stop-color: var(--svg-color--ec02d5, #ec02d5);
}

.x8jrj_d1z {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.78 6.46v4.097l3.549-2.046z");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.xku2qgb8f {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.446 9.15v4.097L21 11.195z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.xqtzposzh {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.896 14.166v4.098l3.549-2.052z");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.z-l8rjstb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.892 11.195v4.098l3.554-2.046z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.zdka_zfyd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.335 6.77v4.097L9.78 8.816z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

</style>
