<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hjukicb4e"/><circle class="rvta_kb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bgram" /></template>
<style>
.hjukicb4e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.553 14.289l3.96-1.891c2.34-.924 3.166-.533 4.607 1.623a18.2 18.2 0 0 0-3.992 4.398c14.454 1.28-.1 19.185-4.564 25.73l2.059-18.725s-5.321.611-5.677.956c-1.573 3.174-3.094 6.302-4.72 9.49l-9.247-9.635l10.209-4.65a18.2 18.2 0 0 0 .566-5.172a146 146 0 0 1-19.132 1.27c12.386-8 26.1-17.285 25.93-3.394Z");
}

.rvta_kb_y {
  cx: 34.87px;
  cy: 14.05px;
  r: 0.75px;
  fill: currentColor;
}

</style>
