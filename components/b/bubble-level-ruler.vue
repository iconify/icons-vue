<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j675s-b4c"/><path class="ms4ioyn0u"/><circle class="z_9ok6h9y"/><circle class="ghc98hd4t"/><path class="czq8txxkn"/><circle class="hy7yzabcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bubble-level-ruler" /></template>
<style>
.czq8txxkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.157 31.866l2-1.09v8M5.498 36.35l37-15.16M6.063 40.56l36.44-23.99M26.308 33.43a2.652 2.652 0 0 1 5.285-.298c.082.838-.183 1.664-.762 2.172c-1.072.94-4.524 3.476-4.524 3.476h5.3M5.498 26.33a6.557 6.557 0 1 0 0-10.042M10.678 5.5v5.965m6.72-5.965v4.393m6.72-4.393v5.965m6.72-5.965v4.393m6.72-4.393v5.965");
}

.ghc98hd4t {
  cx: 8.294px;
  cy: 19.49px;
  r: 1.082px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hy7yzabcj {
  cx: 10.318px;
  cy: 21.57px;
  r: 0.75px;
  fill: currentColor;
}

.j675s-b4c {
  width: 37px;
  height: 37px;
  x: 5.497px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ms4ioyn0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.078 16.15h2.985v10.52h-2.985z");
}

.z_9ok6h9y {
  cx: 39.282px;
  cy: 31.21px;
  r: 1.226px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
