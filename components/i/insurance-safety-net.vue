<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3y8pzbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:insurance-safety-net" /></template>
<style>
.j3y8pzbqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4v16M21 4v16M3 6c3.5 11.5 14.5 11.5 18 0M3 6h18M8 6l.5 6.75M12 6v8.5M16 6l-.5 6.75");
}

</style>
