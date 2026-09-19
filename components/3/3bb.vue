<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="phnkgtr5z"/><path class="dcdv4mj7u"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:3bb" /></template>
<style>
.dcdv4mj7u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.835 19.835c.692-.576 1.438-.84 3.111-.835l.39.002a2.5 2.5 0 0 1 2.499 2.5h0a2.5 2.5 0 0 1-2.5 2.5m-1.921-.001h1.921");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.phnkgtr5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.588 24a2.5 2.5 0 0 1 0 5h-4.125V19h4.125a2.5 2.5 0 0 1 0 5m0 0h-4.125m13.202 0a2.5 2.5 0 0 1 0 5H29.54V19h4.125a2.5 2.5 0 0 1 0 5m0 0H29.54m-17.704 4.157c.69.578 1.436.843 3.11.843h.39a2.5 2.5 0 0 0 2.499-2.5h0a2.5 2.5 0 0 0-2.5-2.499");
}

</style>
