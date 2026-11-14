<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pqik8ebqd"/><path class="upj23cjoi"/><path class="t9n1jmbej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:block-builder" /></template>
<style>
.pqik8ebqd {
  d: path("M4 21.5V3h14M4 7.5L8.5 3M15 3v5.5");
}

.t9n1jmbej {
  d: path("M11 10.75L15 13l4-2.25M15 13v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.upj23cjoi {
  d: path("m15 8.5l4 2.25v4.5l-4 2.25l-4-2.25v-4.5Z");
}

</style>
