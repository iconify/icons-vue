<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1dufir2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dart" /></template>
<style>
.i1dufir2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 20l2.47-2.47m3.72-3.36l-.36-.36q-.88-.88-1.76 0L6.3 15.58q-.89.88 0 1.77l.35.35q.89.89 1.77 0l1.77-1.77q.88-.88 0-1.76m-.18-.18l2.48-2.48m.47-1.24l.83-3.79q.21-.98 1.16-1.3l4.85-1.61q.95-.32.63.63l-1.61 4.85q-.32.95-1.3 1.16l-3.79.83q-.98.21-.77-.77");
}

</style>
