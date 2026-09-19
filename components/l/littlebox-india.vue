<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="go_d9q0oj"/><circle class="abi2t41we"/><path class="bmhbyu83y"/><rect class="jc1oydeao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:littlebox-india" /></template>
<style>
.abi2t41we {
  cx: 10.485px;
  cy: 19.462px;
  r: 0.75px;
  fill: currentColor;
}

.bmhbyu83y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.485 21.642v4.717m2.778-6.185v6.185m-.934-4.717h1.869m2.599-1.468v6.185m-.935-4.717h1.869M7.484 19.244v6.23c0 .49.398.89.89.89h.267m10.759-7.12v6.23c0 .49.398.89.89.89h.267m4.997-.899a1.78 1.78 0 0 1-3.327-.881v-1.157a1.78 1.78 0 1 1 3.56 0v.578h-3.56m5.223-.583a1.78 1.78 0 1 1 3.56 0v1.157a1.78 1.78 0 1 1-3.56 0m0 1.78v-7.12");
}

.go_d9q0oj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.458 21.642l-3.56 4.717m3.56 0l-3.56-4.717m-3.444 4.721a1.78 1.78 0 0 1-1.78-1.78v-1.157a1.78 1.78 0 1 1 3.56 0v1.157a1.78 1.78 0 0 1-1.78 1.78");
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
