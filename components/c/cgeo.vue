<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ly1dteula"/><path class="xh43bcc2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cgeo" /></template>
<style>
.ly1dteula {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4 12.9v27.47l13.34-5.27l13.32 5.27L44 35.1V7.63L30.66 12.9L17.34 7.63ZM21.33 30h5.99m-5.99-11.98h5.99m-5.99 5.99h3.91m-3.91-5.99V30");
}

.xh43bcc2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18 22a4 4 0 0 0-4.23-4A4.17 4.17 0 0 0 10 22.25V26a4 4 0 0 0 4 4h0a4 4 0 0 0 4-4h-4m24-4a4 4 0 0 0-4.24-4A4.17 4.17 0 0 0 30 22.25V26a4 4 0 0 0 4 4h0a4 4 0 0 0 4-4z");
}

</style>
