<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbr6uynae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campfire-grill" /></template>
<style>
.vbr6uynae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 7.5l1.5-3h14l1.5 3M5 20l14-3.5m-14 0L19 20M12 8c1.5 1.5 3 2.5 3 4.25a3 3 0 0 1-6 0C9 10.5 10.5 9.5 12 8");
}

</style>
