<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="adydlicyc"/><path class="abyvnkhga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:3d-printer-lab" /></template>
<style>
.abyvnkhga {
  d: path("M6.5 12.75L10 14.5l3.5-1.75M10 14.5v4m-7.5 3h9.3M17 15v2.75l-2 3.75h6l-2-3.75V15m-2.75 0h3.5");
}

.adydlicyc {
  d: path("M7 2.5h6V5l-3 3l-3-3Zm6.422 14.289L10 18.5l-3.5-1.75v-4L10 11l3.488 1.744");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
