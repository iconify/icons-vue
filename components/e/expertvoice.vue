<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="bdn60qawl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:expertvoice" /></template>
<style>
.bdn60qawl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.291 3.77L13.946 25.291a.898.898 0 0 0 .7 1.461h6.379c.66 0 1.066.72.725 1.285l-8.731 14.45m3.177 1.553l17.498-21.713a.898.898 0 0 0-.7-1.461h-6.379a.847.847 0 0 1-.724-1.285L34.544 5.26");
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

</style>
