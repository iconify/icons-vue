<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr-g9cbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:import-fill" /></template>
<style>
.xr-g9cbin {
  fill: currentColor;
  d: path("M8.293 12.707a.999.999 0 1 1 1.414-1.414L11 12.586V3a1 1 0 0 1 2 0v9.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0ZM4 9v10a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1a1 1 0 0 1 0-2a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3a1 1 0 0 1 0 2a1 1 0 0 0-1 1");
}

</style>
