<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ulve6emah"/><path class="d-63bob2d"/><path class="vddqnrbls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:governance-token" /></template>
<style>
.d-63bob2d {
  d: path("M3.5 9v5.5a8.5 5.5 0 0 0 17 0V9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ulve6emah {
  d: path("M3.5 9a8.5 5.5 0 1 0 17 0a8.5 5.5 0 1 0-17 0Z");
}

.vddqnrbls {
  d: path("m9 9l2 2l4-4");
}

</style>
