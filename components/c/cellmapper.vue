<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hmyp92ols"/><path class="mxfx3ghnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cellmapper" /></template>
<style>
.hmyp92ols {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.235 19.563a31.5 31.5 0 0 1 15.622-3.647c5.024.14 9.74 1.439 13.899 3.655m-25.794 7.003a23.45 23.45 0 0 1 12.76-2.676a23.5 23.5 0 0 1 9.316 2.667M16.635 33.48a15.95 15.95 0 0 1 9.943-1.59c1.714.283 3.33.821 4.787 1.58");
}

.mxfx3ghnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.85 40.076a8.52 8.52 0 0 0-7.7 0L5.5 12.534c5.52-2.941 11.815-4.61 18.5-4.61s12.98 1.669 18.5 4.61z");
}

</style>
