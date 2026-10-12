<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_8lfaclw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jackpot-sharp" /></template>
<style>
.o_8lfaclw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14h6v7.25h-6zm6-3.5h6.5v10.75h-6.5zm6.5 3.5h6v7.25h-6zm-12.5 3.5h6m6.5 0h6M8.75 14h6.5m-6.5 3.5h6.5M12 2.75l.27 1.98l1.98.27l-1.98.27L12 7.25l-.27-1.98L9.75 5l1.98-.27z");
}

</style>
