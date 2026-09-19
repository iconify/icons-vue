<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z0f3ynbfe"/><path class="b1oo41wfp"/><path class="o0xzzubgi"/><path class="e6bcv2jya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:d20-calculator" /></template>
<style>
.b1oo41wfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.5 28l-2.2 6.8l4.8 5.2l6.9-1.5l2.2-6.8l-4.8-5.2z");
}

.e6bcv2jya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.7 35.7L30 34.2l4.3-4.3zm-9.4-.9l3.7-.6m4.3-4.3l1.1-3.4m2.6 12l-2.3-2.8");
}

.o0xzzubgi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.5 28l1.5 6.2l1.1 5.8l4.6-4.3l4.5-4l-5.9-1.8z");
}

.z0f3ynbfe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4m14.5 0v37M5.5 24h37m-13.8-8.6h9M11.3 29.3l8 7.9m-.1-7.9l-8 8m4.1-26.4v9m-4.5-4.5h9");
}

</style>
