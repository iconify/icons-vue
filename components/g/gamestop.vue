<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="tuoi5lt2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gamestop" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tuoi5lt2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.116 32.627zc-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2v1.3c0 1.1-.9 2-2 2M23.62 17.373c0-1.1.9-2 2-2s2 .9 2 2v3.3m-4-5.3v5.4m4-3.4c0-1.1.9-2 2-2s2 .9 2 2v3.3m-19.1 11.054c.5.6 1.1.9 2 .9h1.2c1.1 0 2-.9 2-2s-.9-2-2-2h-1.3c-1.1 0-2-.9-2-2s.9-2 2-2h1.2c.9 0 1.5.2 2 .9m2.99.1v6c0 .6.4 1 1 1h.3m-2.4-5.4h2.2m-.094-8.554c0 1.1-.9 2-2 2s-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2m0 3.3v-5.4m15.7 4.4c-.3.6-1 1-1.7 1c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2v.7h-4M30.32 30.627c0 1.1.9 2 2 2s2-.9 2-2v-1.3c0-1.1-.9-2-2-2s-2 .9-2 2m0-2.1v8M15.784 15.473c0-1.5-1.2-2.7-2.7-2.7s-2.7 1.2-2.7 2.7v2.7c0 1.5 1.2 2.6 2.7 2.6s2.7-1.2 2.7-2.6h-2.7");
}

</style>
