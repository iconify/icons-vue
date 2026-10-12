<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4eza768j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lattice-tower" /></template>
<style>
.k4eza768j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 21.25c3.5-4.5 5.25-10.75 5.75-16.5h3c.5 5.75 2.25 12 5.75 16.5m-10 0a2.75 2.75 0 0 1 5.5 0m-8.25-5.5h11M8.75 10.5h6.5M12 4.75v-2");
}

</style>
