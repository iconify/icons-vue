<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="h60ap67ws"/><path class="k0szy4bby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ioc-indicator" /></template>
<style>
.h60ap67ws {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21.25V2.75m0 .75h13.5l-2.75 4.25L18.5 12H5Zm5.5 2v2");
}

.k0szy4bby {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 10h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
