<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ko39o5bky"/><path class="upzdk5bkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:allergy-list" /></template>
<style>
.ko39o5bky {
  d: path("M12.6 19H3V2.5h13v9.8M6 7h7m-7 3.5h7M6 14h4.5m7.5.25l1.323 1.93l2.243.661l-1.426 1.854l.064 2.339L18 20.25l-2.204.784l.064-2.339l-1.426-1.854l2.243-.661Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.upzdk5bkq {
  fill: currentColor;
  d: path("M17.25 18a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

</style>
