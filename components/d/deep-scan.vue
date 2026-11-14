<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k69p78t_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deep-scan" /></template>
<style>
.k69p78t_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.671 3.335l4.146 2.073a1.5 1.5 0 0 1 0 2.684l-4.146 2.073a1.5 1.5 0 0 1-1.342 0L7.183 8.092a1.5 1.5 0 0 1 0-2.684l4.146-2.073a1.5 1.5 0 0 1 1.342 0M4.5 11.75L12 15.5l7.5-3.75m-15 5L12 20.5l7.5-3.75m-17-2.5h19");
}

</style>
