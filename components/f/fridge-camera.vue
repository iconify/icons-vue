<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="maxto3b7g"/><path class="jgxk1xqgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fridge-camera" /></template>
<style>
.jgxk1xqgy {
  d: path("M16.75 19a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.maxto3b7g {
  d: path("M11.7 21.5H3.5v-19h13v9.9m-13-2.9h13M6.5 5v2m0 5v4.5m8 .25H16l.75-1.5h2l.75 1.5h2v4.75h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
