<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzfqyybum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coral" /></template>
<style>
.rzfqyybum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 18.75V9.5m0 5.5c-2.75 0-4.5-1.75-4.5-4.5v-3m4.5 5c2.75 0 4.5-1.75 4.5-4.5V4.25m-9 6.25c-2 0-3.25-1.25-3.25-3.25V5.5m12.25 4c2.5 0 3.75-1.25 3.75-3.25M7.5 7.5v-3m-1 16.75c.5-1.5 2-2.5 5.5-2.5s5 1 5.5 2.5Z");
}

</style>
