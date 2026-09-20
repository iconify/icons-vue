<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="vs74-lbdp"/><path class="tucubo3yo"/></g><path class="bi8qd1b6p"/><g class="y9tr6bcfx"><path class="xft04qnlk"/><path class="t8jxhgbqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:beautyplus" /></template>
<style>
.bi8qd1b6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.027 17.746c-.125.017-1.366-1.43-1.467-1.507s-1.83-.88-1.847-1.005c-.018-.125 1.43-1.366 1.507-1.466s.88-1.83 1.005-1.847s1.366 1.43 1.467 1.507s1.83.88 1.847 1.005c.018.125-1.43 1.365-1.507 1.466s-.88 1.83-1.005 1.847");
}

.t8jxhgbqt {
  d: path("M24.68 22.451a2.06 2.06 0 0 1-4.08.561a2.059 2.059 0 0 1 4.08-.56");
}

.tucubo3yo {
  d: path("M8.807 13.007c.712-.208 1.259-.623 1.736-1.717c.216-.492.6-.914 1.17-.993l2.721-.374c.57-.079 1.055.224 1.395.64c.71.869 1.317 1.143 2.004 1.18");
}

.vs74-lbdp {
  d: path("m9.262 12.92l25.933-3.568a5.5 5.5 0 0 1 6.213 4.708l2.04 14.808a5.5 5.5 0 0 1-4.71 6.211l-25.933 3.569a5.5 5.5 0 0 1-6.213-4.708l-2.04-14.808a5.5 5.5 0 0 1 4.71-6.212");
}

.xft04qnlk {
  d: path("M31.982 23.333c.602 4.374-2.457 8.408-6.833 9.01s-8.412-2.456-9.014-6.83a7.995 7.995 0 0 1 6.833-9.01a7.997 7.997 0 0 1 9.014 6.83m-15.847 2.181l-1.29-9.373");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
