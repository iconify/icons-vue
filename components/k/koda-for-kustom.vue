<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vy4k2vbhx"/><circle class="ba21indcm"/><path class="tjzcsbbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:koda-for-kustom" /></template>
<style>
.ba21indcm {
  cx: 35.864px;
  cy: 35.657px;
  r: 6.299px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tjzcsbbom {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.453 5.554h-8.467c-3.02 0-4.76 2.236-4.742 5.252v10.589c.029 4.881 13.209-2.932 13.209-9.666z");
}

.vy4k2vbhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.292 8.516l.045 21.515c.013 6.03-6.487 12.561-13.864 12.468c-1.815-.023-2.93-1.211-2.926-3.196l.045-21.605c.015-6.882 6.004-12.18 13.954-12.198c1.89-.004 2.743 1.478 2.746 3.016");
}

</style>
