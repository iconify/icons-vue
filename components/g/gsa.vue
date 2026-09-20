<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ule8g-b8n"/><path class="y6030vota"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gsa" /></template>
<style>
.ule8g-b8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4m-1.163 20.27h-4.631");
}

.y6030vota {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.55 29.314l3.475-10.66L38.5 29.346m-17.763-1.172c.656.854 1.478 1.172 2.621 1.172h1.583a2.667 2.667 0 0 0 2.667-2.667v-.012A2.667 2.667 0 0 0 24.941 24h-1.746a2.67 2.67 0 0 1-2.67-2.67a2.676 2.676 0 0 1 2.676-2.676h1.574c1.144 0 1.966.318 2.622 1.172m-10.814 2.37a3.542 3.542 0 0 0-7.083 0v3.608a3.542 3.542 0 0 0 7.083 0H13.04");
}

</style>
