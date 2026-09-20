<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="zyp-nct8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-open-28-filled" /></template>
<style>
.zyp-nct8u {
  fill: currentColor;
  d: path("M5.754 3a3.75 3.75 0 0 0-3.75 3.75v11.765l2.65-5.533A5.25 5.25 0 0 1 9.39 10h13.612v-.25A3.75 3.75 0 0 0 19.25 6h-5.587a.25.25 0 0 1-.177-.073l-2.12-2.122A2.75 2.75 0 0 0 9.421 3zM2.116 21.764l-.008.021a1.637 1.637 0 0 0 1.533 2.21h15.974a3.75 3.75 0 0 0 3.244-1.868l3.768-6.497c1.063-1.834-.26-4.13-2.379-4.13H9.39a3.75 3.75 0 0 0-3.382 2.13l-3.843 8.02z");
}

</style>
