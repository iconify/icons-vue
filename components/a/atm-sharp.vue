<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmbnc06bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:atm-sharp" /></template>
<style>
.vmbnc06bz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17V3h18v14M7 6h10M3 10h4m10 0h4M7 10h10v11H7zm3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
