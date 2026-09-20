<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dmca72itk"/><path class="q5uf-4-mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:doc-scanner" /></template>
<style>
.dmca72itk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M5.5 31h37");
}

.q5uf-4-mu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 22.873v-9.246h2.08a4.045 4.045 0 0 1 4.046 4.045v1.156a4.045 4.045 0 0 1-4.046 4.045zm23-3.101v.038a3.063 3.063 0 0 1-6.126 0v-3.12a3.063 3.063 0 0 1 6.126 0v.038M20.937 19.81a3.063 3.063 0 0 0 6.126 0v-3.12a3.063 3.063 0 0 0-6.126 0z");
}

</style>
