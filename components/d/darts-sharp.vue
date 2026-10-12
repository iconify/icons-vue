<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp1awzb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:darts-sharp" /></template>
<style>
.pp1awzb7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 20l2.47-2.47m3.72-3.36l-.36-.36l-.88-.88l-.88.88l-1.77 1.77l-.89.88l.89.89l.35.35l.89.89l.88-.89l1.77-1.77l.88-.88zm-.18-.18l2.48-2.48m.47-1.24l.83-3.79l.21-.98l.95-.32l4.85-1.61l.95-.32l-.32.95l-1.61 4.85l-.32.95l-.98.21l-3.79.83l-.98.21z");
}

</style>
