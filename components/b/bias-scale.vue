<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8nhevxln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bias-scale" /></template>
<style>
.a8nhevxln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.25 8.5l11.5-2.75M12 7.1v14.15m-3.25 0h6.5m-9-12.75l-3 5.75m3-5.75l3 5.75m8.5-8.5l-3 5.5m3-5.5l3 5.5m-18 3h7a3.5 3.5 0 0 1-7 0m11.5-3h7a3.5 3.5 0 0 1-7 0");
}

</style>
