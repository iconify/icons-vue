<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-cdf_b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airline-seat-flat-rounded" /></template>
<style>
.w-cdf_b_j {
  fill: currentColor;
  d: path("M10 14q-.425 0-.712-.288T9 13V9q0-.825.588-1.412T11 7h7q1.65 0 2.825 1.175T22 11v2q0 .425-.288.713T21 14zm11 3H3q-.425 0-.712-.288T2 16t.288-.712T3 15h18q.425 0 .713.288T22 16t-.288.713T21 17M2.875 13.125Q2 12.25 2 11t.875-2.125T5 8t2.125.875T8 11t-.875 2.125T5 14t-2.125-.875");
}

</style>
