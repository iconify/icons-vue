<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h8jwz9bct"/><path class="efrpdw-8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:caffeine" /></template>
<style>
.efrpdw-8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.882 7.132h4.353a3.265 3.265 0 0 1 3.265 3.265v6.53a3.265 3.265 0 0 1-3.265 3.264h-4.353M5.5 40.868h37");
}

.h8jwz9bct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.765 7.132h26.117v21.765a7.62 7.62 0 0 1-7.617 7.618H13.118A7.62 7.62 0 0 1 5.5 28.897v-18.5a3.266 3.266 0 0 1 3.265-3.265");
}

</style>
