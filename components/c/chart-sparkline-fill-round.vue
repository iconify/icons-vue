<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulwrttbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-sparkline-fill-round" /></template>
<style>
.ulwrttbjx {
  fill: currentColor;
  d: path("m16.338 9.45l-4.464 8.036a1 1 0 0 1-1.474.314l-3.306-2.48l-3.387 3.387a.999.999 0 1 1-1.414-1.414l4-4A1 1 0 0 1 7.6 13.2l3.083 2.312l4.116-7.41a3.83 3.83 0 1 1 1.539 1.348");
}

</style>
