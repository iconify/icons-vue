<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="c67jk9bkn"/><path class="yfocjbc_l"/></g><rect class="tnpsh9bza"/><path class="d6a2kxbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diskdigger-pro" /></template>
<style>
.c67jk9bkn {
  cx: 29.448px;
  cy: 17.697px;
  r: 7.568px;
}

.d6a2kxbka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 30.066l2.753-9.504a1.58 1.58 0 0 1 1.517-1.14h21.288a1.58 1.58 0 0 1 1.517 1.14l2.753 9.504M9.485 33.039h19.858");
}

.tnpsh9bza {
  width: 29.828px;
  height: 9.664px;
  x: 4.5px;
  y: 28.207px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.859px;
  ry: 1.859px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yfocjbc_l {
  d: path("m34.799 23.049l.881.881m0 2.203l5.617 5.617l2.203-2.204l-5.616-5.616H35.68z");
}

</style>
