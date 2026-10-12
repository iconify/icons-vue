<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_omgjx7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glider" /></template>
<style>
.u_omgjx7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a1.75 1.75 0 0 1 1.75 1.75v7.25l-1.15 8h-1.2l-1.15-8V4.5A1.75 1.75 0 0 1 12 2.75M12 5v2.25m-9.25 3L10.25 9m3.5 0l7.5 1.25m-12.5 9.5h6.5");
}

</style>
