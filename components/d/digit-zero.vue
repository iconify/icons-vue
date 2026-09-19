<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hiltg1b3g"/><path class="gplbldbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:digit-zero" /></template>
<style>
.gplbldbjh {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m6.975 42.795Q36.475 48 32 48q-4.496 0-7.248-3.516T22 31.948q0-8.85 3.025-12.74Q27.525 16.001 32 16c4.475-.001 5.315 1.082 6.996 3.25Q42 23.098 42 32.012q0 8.891-3.025 12.783");
}

.hiltg1b3g {
  fill: currentColor;
  d: path("M33.9 21.676q-.83-.695-1.9-.695c-1.07 0-1.352.232-1.912.695s-.994 1.293-1.303 2.49q-.608 2.33-.608 7.846q0 5.514.546 7.578q.544 2.063 1.377 2.746q.83.685 1.9.684c1.07-.001 1.352-.23 1.912-.693q.84-.697 1.303-2.492q.608-2.308.608-7.822q0-5.516-.546-7.58q-.544-2.062-1.377-2.757");
}

</style>
