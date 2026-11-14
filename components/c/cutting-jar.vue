<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w-yyxnb8f"/><path class="v5xmccbks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cutting-jar" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5xmccbks {
  d: path("M11.5 19c0-5 0-9 .5-12.5m0 1c0-3 2.5-5 5.5-5c0 3-2.5 5-5.5 5Zm-5.5 8h11");
}

.w-yyxnb8f {
  d: path("M5.5 9h1v10.5a2 2 0 0 0 2 2h7a2 2 0 0 0 2-2V9h1");
}

</style>
