<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="foxfepe7h"/><path class="zrwasybdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flash-trigger" /></template>
<style>
.foxfepe7h {
  d: path("M11.5 2.5L4 13h5.5L8 21.5L15 11H9.5Zm4.862 5a7 7 0 0 1 0 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zrwasybdy {
  d: path("M18.469 5.733a9.75 9.75 0 0 1 0 12.534");
}

</style>
