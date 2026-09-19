<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="sdqv56b_s"/><path class="cqu-0eeem"/><path class="brzrvco4m"/><path class="q4npjxbuh"/><path class="ohto4ubie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:codered-mobile-alert" /></template>
<style>
.brzrvco4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.736 7.912c1.204 2.325 2.151 4.908 2.783 7.669c.608 2.642.923 5.459.914 8.373s-.353 5.724-.99 8.364c-.657 2.752-1.622 5.332-2.838 7.648");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cqu-0eeem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.895 5.465c-1.837 1.864-3.997 3.554-6.432 4.998c-2.328 1.405-4.906 2.582-7.68 3.47s-5.563 1.429-8.264 1.648c-2.823.22-5.569.102-8.146-.347");
}

.ohto4ubie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.08 45.395c.393-2.587 1.153-5.228 2.258-7.835a37 37 0 0 1 4.187-7.313a36.3 36.3 0 0 1 5.728-6.18c2.143-1.85 4.431-3.362 6.782-4.512");
}

.q4npjxbuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.29 32.58c2.582-.417 5.334-.513 8.152-.262c2.706.234 5.48.8 8.246 1.717a37 37 0 0 1 7.65 3.525c2.417 1.476 4.566 3.194 6.387 5.075");
}

.sdqv56b_s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.98 28.638a33 33 0 0 1-6.726-4.572c-2.06-1.783-3.97-3.87-5.675-6.24s-3.08-4.844-4.116-7.363a33 33 0 0 1-2.198-7.83");
}

</style>
