<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zle5c2bwm"/><path class="se971gh0e"/><path class="qdxj-lf1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dragon-dance-sharp" /></template>
<style>
.qdxj-lf1w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75h2.5M9 8c1.5-3 3.75-3 5 0s3.75 3 5 0m-7.5-2.25v15.5m5-11v11");
}

.se971gh0e {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 7h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zle5c2bwm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 5l1.5-2.25M3.32 6.01l.61-.52L4.5 5h3.75l.18.73l.39 1.54L9 8l-.18.73l-.39 1.54l-.18.73H3.5l-.12-.74l-.51-3.02l-.12-.74z");
}

</style>
