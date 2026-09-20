<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGMAcQdbjX" x1="-202.298" x2="-202.26" y1="-171.036" y2="-171.046" gradientTransform="matrix(87.822 0 0 -88.533 17792.306 -15114.083)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r73-npb0a"/><stop offset="1" class="xazr-qbyt"/></linearGradient><linearGradient id="SVG3QzO8btT" x1="-202.066" x2="-202.047" y1="-172.644" y2="-172.6" gradientTransform="matrix(87.822 0 0 -88.533 17772.442 -15266.467)" gradientUnits="userSpaceOnUse"><stop offset="0" class="tuulkuo_t"/><stop offset="1" class="w4n1u0bdf"/></linearGradient><linearGradient id="SVGCzqnYbSw" x1="-201.407" x2="-201.407" y1="-173.45" y2="-173.412" gradientTransform="matrix(87.822 0 0 -88.533 17710.573 -15342.2)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6dfhrbcp"/><stop offset="0" class="r73-npb0a"/><stop offset="1" class="w4n1u0bdf"/></linearGradient><linearGradient id="SVGtImID4mZ" x1="-200.902" x2="-200.953" y1="-172.909" y2="-172.897" gradientTransform="matrix(106.198 0 0 -88.551 21355.411 -15295.168)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r73-npb0a"/><stop offset="1" class="fj365kbij"/></linearGradient></defs><path class="c4l8d1bff"/><path class="afjuseeyk"/><path class="tdfom_bfh"/><path fill="url(#SVGMAcQdbjX)" class="dk91m4b_m"/><path class="ezv2s4ocj"/><path fill="url(#SVG3QzO8btT)" class="tbn6o4q6x"/><path fill="url(#SVGCzqnYbSw)" class="y54n-s-of"/><path fill="url(#SVGtImID4mZ)" class="y2z44nb1o"/><path class="s3tsfy3ib"/><path class="mm-a576ks"/><path class="pbni_gl0k"/><path class="m8q8zjbxq"/><path class="zpb5yeejj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-flow" /></template>
<style>
.afjuseeyk {
  fill: var(--svg-color--ffdf51, #ffdf51);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M28.069 30.557v-5.428h-5.385l5.385 5.429");
}

.c4l8d1bff {
  fill: var(--svg-color--bf8e55, #bf8e55);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.dk91m4b_m {
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M25.136 25.129V31h5.824z");
}

.ezv2s4ocj {
  fill: var(--svg-color--ffdf4f, #ffdf4f);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M27.456 22v-4.643h-4.607z");
}

.fj365kbij {
  stop-color: var(--svg-color--ffa829, #ffa829);
}

.m8q8zjbxq {
  fill: var(--svg-color--ff8900, #ff8900);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M21.069 18.018v-5.872h-5.824zm1.615 7.111V31h5.824z");
}

.mm-a576ks {
  fill: var(--svg-color--ffb700, #ffb700);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M21.084 25.085v-5.871H15.26z");
}

.pbni_gl0k {
  fill: var(--svg-color--ffcd25, #ffcd25);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M22.849 17.357v5.871h5.824z");
}

.r73-npb0a {
  stop-color: var(--svg-color--ffd441, #ffd441);
}

.s3tsfy3ib {
  fill: var(--svg-color--ffb700, #ffb700);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M21.082 30.968v-7.1h-7.043z");
}

.s6dfhrbcp {
  stop-color: var(--svg-color--ffd642, #ffd642);
}

.tbn6o4q6x {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M29.643 20.894v-5.871h-5.824z");
}

.tdfom_bfh {
  fill: var(--svg-color--ff8900, #ff8900);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M28.674 27.479v-5.871h-5.825z");
}

.tuulkuo_t {
  stop-color: var(--svg-color--ffd754, #ffd754);
}

.w4n1u0bdf {
  stop-color: var(--svg-color--ffb532, #ffb532);
}

.xazr-qbyt {
  stop-color: var(--svg-color--ffb047, #ffb047);
}

.y2z44nb1o {
  fill-opacity: var(--svg-fill-opacity--0-88, 0.88);
  d: path("M21.082 19.2v-5.875h-7.043l5.8 5.873h1.244");
}

.y54n-s-of {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M19.716 10v5.871h5.824z");
}

.zpb5yeejj {
  fill: var(--svg-color--fff, #fff);
  d: path("m26.342 25.129l-1.885-1.901h-1.608v-5.871h3.286l-1.474-1.486h-3.592l.013 3.325V31h1.602v-5.871z");
}

</style>
