<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yduhofb9b"/><path class="zgelycc0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lockout-breaker" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yduhofb9b {
  d: path("M11.7 18.5H2.5v-16h15v7.7");
}

.zgelycc0s {
  d: path("M6 6h4v9H6Zm2 4.5h6m.5 6h7v5h-7Zm1.5 0V15a2 2 0 0 1 4 0v1.5");
}

</style>
