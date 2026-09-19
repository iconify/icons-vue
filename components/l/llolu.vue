<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="fytel3bzn"/><ellipse class="w4d4x4krx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:llolu" /></template>
<style>
.fytel3bzn {
  d: path("M15.236 10.707v16.547C15.236 38.822 4.5 37.23 4.5 37.23V21.01c0-11.656 10.736-10.303 10.736-10.303m11.602.047v16.547c0 11.568-11.602 9.94-11.602 9.94v-16.22c0-11.656 11.602-10.267 11.602-10.267");
}

.w4d4x4krx {
  cx: 35.169px;
  cy: 28.987px;
  rx: 8.331px;
  ry: 8.354px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
