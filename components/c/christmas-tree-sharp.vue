<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="x3b2mkr-t"/><path class="ad3oim8dr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:christmas-tree-sharp" /></template>
<style>
.ad3oim8dr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 13.5h.01M14 17h.01M9 17.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x3b2mkr-t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.12 3.02l.29.63l.12.27l.3.03l.68.08l.3.03l-.22.2l-.51.47l-.22.2l.06.29l.14.67l.06.3l-.26-.15l-.6-.34l-.26-.15l-.26.15l-.6.34l-.26.15l.06-.3l.14-.67l.06-.29l-.22-.2l-.51-.47l-.22-.2l.3-.03l.68-.08l.3-.03l.12-.27l.29-.63l.12-.27zm.33 5.87l2.85 2.47l.45.39H14.5l.42.42l2.91 2.91l.42.42H16l.47.37l3.56 2.76l.47.37h-17l.47-.37l3.56-2.76l.47-.37H5.75l.42-.42l2.91-2.91l.42-.42H8.25l.45-.39l2.85-2.47l.45-.39zM12 19v2.25");
}

</style>
