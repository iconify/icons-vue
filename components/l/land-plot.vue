<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbwbstbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:land-plot" /></template>
<style>
.rbwbstbji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.24 19.38l3.27-5.76Q7 12.75 8 12.75h12.25q1 0 .51.87l-3.27 5.76q-.49.87-1.49.87H3.75q-1 0-.51-.87M12 16.5V7.25m.56-4.28l4.63 1.81q.56.22 0 .44l-4.63 1.81q-.56.22-.56-.38v-3.3q0-.6.56-.38");
}

</style>
