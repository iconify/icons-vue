<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc0al21eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:controlled-burn" /></template>
<style>
.oc0al21eq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c4 3.75 6 7 6 10.25a6 6 0 0 1-12 0C6 10 7.25 8 9 6.5c.25 2 1 3.25 2 3.75C10.75 7.5 11 5 12 2.5m-9.5 19H5m3 0h8m3 0h2.5");
}

</style>
