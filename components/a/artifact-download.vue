<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="koqo0hbim"/><path class="a6_89kyto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:artifact-download" /></template>
<style>
.a6_89kyto {
  d: path("m3 6l7 3.5L17 6m-7 3.5V16M6.5 4.25l7 3.5M18 14.5V21m-2.75-2.75L18 21l2.75-2.75");
}

.koqo0hbim {
  d: path("M15.235 13.383L10 16l-7-3.5V6l7-3.5L17 6v5.674");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
