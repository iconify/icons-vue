<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y7iorybnp"/><path class="cdlhv-brs"/><path class="isprrmb2n"/><path class="khxzvac0s"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:game-space" /></template>
<style>
.cdlhv-brs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.354 31.58c-2.974 1.386-6.476 3.995-6.476 3.995l-.338-.677s-3.097.46-5.04 1.546m21.707-2.886c1.16-3.067 7.174-9.25 7.174-15.747s-2.005-9.275-2.005-9.275l-1.522 2.488S27.666 9.188 24 9.188s-6.854 1.836-6.854 1.836l-1.522-2.488s-2.005 2.778-2.005 9.275s6.014 12.68 7.174 15.747");
}

.isprrmb2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 36.794c2.918 0 2.12.266 2.99-.459s3.647-4.564 4.54-6.183s1.057-5.654 1.057-5.654m-6.732 2.599c.555-2.463 3.116-3.695 5.845-5.337c-.097 1.618-1.087 2.337-2.609 2.738s-2.027.43-2.027.43m2.729-14.423c.252 4.347-1.5 7.656-1.5 7.656c1.221.918-1.025 4.275-3.344 6.69");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.khxzvac0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.646 31.58c2.974 1.386 6.476 3.995 6.476 3.995l.338-.677s3.097.46 5.04 1.546");
}

.y7iorybnp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 36.794c-2.918 0-2.12.266-2.99-.459s-3.647-4.564-4.54-6.183s-1.057-5.654-1.057-5.654m6.732 2.599c-.555-2.463-3.116-3.695-5.845-5.337c.097 1.618 1.087 2.337 2.609 2.738s2.027.43 2.027.43m-2.729-14.423c-.252 4.347 1.5 7.656 1.5 7.656c-1.221.918 1.025 4.275 3.344 6.69");
}

</style>
