<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ncxtxyvfh"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:line-dictionary-cn-en" /></template>
<style>
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

.ncxtxyvfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.436 33.11a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0v.65h-4m5.816 2.65v-5.3m4 5.3v-3.3a2 2 0 1 0-4 0m-16.447 3.3v-5.3m4 5.3v-3.3a2 2 0 1 0-4 0m-1.816 2.292a2 2 0 0 1-3.736-.993v-1.3a2 2 0 0 1 3.734-.996m10.634-3.429l-3 10.15m1.559-14.711v-8.015l6.062 8.015v-8.015m2.246 4.008h2.015m2.005 4.007h-4.02v-8.015h4.02m-16.497 0v8.015m-2.005-8.015h4.019m-4.019 8.015h4.019m-10.028-8.015v8.015h4.02M10.5 42.5v-37");
}

</style>
