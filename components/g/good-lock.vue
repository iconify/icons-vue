<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ot61p6b2v"/><path class="aeyj5hbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:good-lock" /></template>
<style>
.aeyj5hbyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 34.31h-.1a4.502 4.502 0 0 1-8.9-.944a4.5 4.5 0 0 1 8.9-.945h.1M24 42.5v-8.189m0-1.891V24m0-10.31h.1a4.502 4.502 0 0 1 8.9.944a4.5 4.5 0 0 1-8.9.945H24M24 5.5v8.189m0 1.89V24");
}

.ot61p6b2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M5.5 24h37");
}

</style>
