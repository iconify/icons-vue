<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn_9t6mmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-import-round" /></template>
<style>
.zn_9t6mmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12V7.687a2 2 0 0 0-1.114-1.793L16.5 4.222m0 0l-3.614-1.785a2 2 0 0 0-1.772 0l-7 3.457A2 2 0 0 0 3 7.687v8.626a2 2 0 0 0 1.114 1.793l6.093 3.008A1.243 1.243 0 0 0 12 20v-9.111M3.32 6.602L12 10.89l8.68-4.287M18 15l-3 3l3 3m-3-3h6");
}

</style>
