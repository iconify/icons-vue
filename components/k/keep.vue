<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p_1cj_asq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keep" /></template>
<style>
.p_1cj_asq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.37 5.5a2.82 2.82 0 0 0-2.78 2.86v31.07a2.83 2.83 0 0 0 4.7 2.35l.11-.1l.08-.09L24 28.07l13.57 13.56a2.82 2.82 0 1 0 4.06-3.91l-.08-.08L26 22.11a2.85 2.85 0 0 0-2-.86a2.8 2.8 0 0 0-2.14 1L11.23 32.86V8.36A2.82 2.82 0 0 0 8.45 5.5ZM28 24.07l13.52-13.59a2.83 2.83 0 0 0 0-4a2.87 2.87 0 0 0-2.11-.85a2.78 2.78 0 0 0-1.93.86L22 22.05");
}

</style>
