<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow2aums1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airplane-top-view" /></template>
<style>
.ow2aums1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.483 4.871l-.046.596a1.5 1.5 0 0 1-.435.945l-2.357 2.357a1.5 1.5 0 0 0-.39 1.443l1.357 5.159a1.3 1.3 0 0 1-.339 1.256a.562.562 0 0 1-.891-.128l-1.743-3.178a1.406 1.406 0 0 0-2.227-.318l-.887.886a1.5 1.5 0 0 0-.439 1.061v.878a1.5 1.5 0 0 1-.44 1.061l-.002.003a.488.488 0 0 1-.764-.094l-1.076-1.794a1.5 1.5 0 0 0-.515-.515l-1.794-1.076a.488.488 0 0 1-.094-.764l.003-.003a1.5 1.5 0 0 1 1.06-.439h.879a1.5 1.5 0 0 0 1.061-.439l.886-.887a1.406 1.406 0 0 0-.318-2.227L6.794 6.911a.563.563 0 0 1-.128-.891a1.3 1.3 0 0 1 1.256-.34l5.159 1.358a1.5 1.5 0 0 0 1.442-.39l2.358-2.357a1.5 1.5 0 0 1 .945-.435l.596-.046a.988.988 0 0 1 1.061 1.061M7.5 18q-1.25 2.25-4 3");
}

</style>
