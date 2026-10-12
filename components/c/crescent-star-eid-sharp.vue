<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="q3r1ykb8g"/><path class="i8vqfs_ez"/><path class="du0p_jb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crescent-star-eid-sharp" /></template>
<style>
.du0p_jb0p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 4.5h.01");
}

.i8vqfs_ez {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.14 9.07l.55 1.22l.14.32l.35.04l1.33.14l.34.03l-.26.24l-.99.89l-.26.24l.07.34l.28 1.3l.07.35l-.3-.18l-1.16-.67l-.3-.17l-.3.17l-1.16.67l-.3.18l.07-.35l.28-1.3l.07-.34l-.26-.24l-.99-.89l-.26-.24l.34-.03l1.33-.14l.35-.04l.14-.32l.55-1.22l.14-.32z");
}

.q3r1ykb8g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.88 4.01a8.5 8.5 0 1 0 7.42 11.87a7 7 0 1 1-7.42-11.87Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
