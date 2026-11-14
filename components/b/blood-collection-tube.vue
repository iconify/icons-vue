<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmtknzmob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blood-collection-tube" /></template>
<style>
.tmtknzmob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 2.5h3.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 13.75 6h-3.5A1.75 1.75 0 0 1 8.5 4.25a1.75 1.75 0 0 1 1.75-1.75M9 6v13a3 3 0 0 0 6 0V6m-6 7h6");
}

</style>
