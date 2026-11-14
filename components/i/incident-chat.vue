<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="txgdv98gp"/><path class="armedwb3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:incident-chat" /></template>
<style>
.armedwb3a {
  d: path("m12 5.5l6 9.75H6ZM12 9v2.25m0 2h.01");
}

.txgdv98gp {
  d: path("M4.5 2.5h15a2 2 0 0 1 2 2V16a2 2 0 0 1-2 2H10l-4.5 3.5V18h-1a2 2 0 0 1-2-2V4.5a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
