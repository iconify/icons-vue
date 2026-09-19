<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u5oaiccsf"/><path class="k0f9d4mmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:her" /></template>
<style>
.k0f9d4mmh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.131 30V19h3.575c2.063 0 3.713 1.65 3.713 3.713s-1.65 3.712-3.713 3.712h-3.575m3.839-.012L37.419 30");
}

.u5oaiccsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M11.65 19.319v10.362M18.169 19v11m-7.288-5.5h7.288m3.712 5.5h5.5m-5.5-11h5.5m-5.5 3.781h3.575m-3.575 3.438h3.575M21.881 19v11");
}

</style>
