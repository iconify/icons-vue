<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGFogtQd3v" x1="-67.907" x2="-67.857" y1="-308.551" y2="-308.564" gradientTransform="matrix(87.822 0 0 -88.533 5984.532 -27290.617)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r73-npb0a"/><stop offset="1" class="xazr-qbyt"/></linearGradient><linearGradient id="SVGrE49Mbwb" x1="-67.674" x2="-67.647" y1="-310.121" y2="-310.063" gradientTransform="matrix(87.822 0 0 -88.533 5964.667 -27443)" gradientUnits="userSpaceOnUse"><stop offset="0" class="tuulkuo_t"/><stop offset="1" class="w4n1u0bdf"/></linearGradient><linearGradient id="SVGY4QxCdjl" x1="-67.029" x2="-67.029" y1="-310.91" y2="-310.86" gradientTransform="matrix(87.822 0 0 -88.533 5902.8 -27518.733)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6dfhrbcp"/><stop offset="0" class="r73-npb0a"/><stop offset="1" class="w4n1u0bdf"/></linearGradient><linearGradient id="SVGLLOQadKw" x1="-66.252" x2="-66.32" y1="-310.377" y2="-310.362" gradientTransform="matrix(106.198 0 0 -88.551 7048.428 -27474.167)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r73-npb0a"/><stop offset="1" class="fj365kbij"/></linearGradient></defs><path class="ed2ih9byj"/><path class="kspeehbng"/><path fill="url(#SVGFogtQd3v)" class="ew1qxfbep"/><path class="d34sr3epw"/><path fill="url(#SVGrE49Mbwb)" class="kuh4f6-2u"/><path fill="url(#SVGY4QxCdjl)" class="tnpeueb7r"/><path fill="url(#SVGLLOQadKw)" class="fnzzizb-x"/><path class="xraqhibde"/><path class="y0gs32v-r"/><path class="gg5-isrvl"/><path class="dhoyjtbuv"/><path class="h008x5bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-flow" /></template>
<style>
.d34sr3epw {
  fill: var(--svg-color--ffdf4f, #ffdf4f);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M22.608 18v-6.191h-6.142z");
}

.dhoyjtbuv {
  fill: var(--svg-color--ff8900, #ff8900);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M14.092 12.691V4.862H6.326zm2.154 9.48V30h7.766z");
}

.ed2ih9byj {
  fill: var(--svg-color--ffdf51, #ffdf51);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M23.426 29.41v-7.238h-7.18z");
}

.ew1qxfbep {
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M19.515 22.171V30h7.766z");
}

.fj365kbij {
  stop-color: var(--svg-color--ffa829, #ffa829);
}

.fnzzizb-x {
  fill-opacity: var(--svg-fill-opacity--0-88, 0.88);
  d: path("M14.11 14.262V6.433H4.719l7.732 7.83z");
}

.gg5-isrvl {
  fill: var(--svg-color--ffcd25, #ffcd25);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M16.465 11.809v7.829h7.766z");
}

.h008x5bmt {
  fill: var(--svg-color--fff, #fff);
  d: path("m21.122 22.172l-2.513-2.534h-2.144l.001-7.829h4.381l-1.965-1.98h-4.79l.018 4.433V30h2.136v-7.828z");
}

.kspeehbng {
  fill: var(--svg-color--ff8900, #ff8900);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M24.231 25.306v-7.829h-7.765z");
}

.kuh4f6-2u {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M25.524 16.525V8.7h-7.765l7.766 7.829");
}

.r73-npb0a {
  stop-color: var(--svg-color--ffd441, #ffd441);
}

.s6dfhrbcp {
  stop-color: var(--svg-color--ffd642, #ffd642);
}

.tnpeueb7r {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M12.288 2v7.829h7.766z");
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

.xraqhibde {
  fill: var(--svg-color--ffb700, #ffb700);
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M14.11 29.958v-9.471H4.719z");
}

.y0gs32v-r {
  fill: var(--svg-color--ffb700, #ffb700);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M14.112 22.114v-7.829H6.346z");
}

</style>
