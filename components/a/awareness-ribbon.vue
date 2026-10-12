<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwcf3obin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:awareness-ribbon" /></template>
<style>
.rwcf3obin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 20.75l7-10.25C15.5 8.6 15.4 3.25 12 3.25S8.5 8.6 9.75 10.5l.75 1.1m3 4.45l3.25 4.7");
}

</style>
