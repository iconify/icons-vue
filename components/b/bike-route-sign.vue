<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wmr9rhlky"/><path class="iu4fj2b6v"/><path class="oz2_yebcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-route-sign" /></template>
<style>
.iu4fj2b6v {
  d: path("M7 11.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.oz2_yebcj {
  d: path("M9 11.5L11 8h3.5l-2.25 3.5ZM14.5 8l.5 3.5M14.5 8L14 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wmr9rhlky {
  d: path("M4 2.5h16v14H4Zm8 14v5");
}

</style>
