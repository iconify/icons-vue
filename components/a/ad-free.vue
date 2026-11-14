<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fodytqh7n"/><path class="eduusueal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ad-free" /></template>
<style>
.eduusueal {
  d: path("M10.6 14.5H6V9.9m8-.4h4m-14.5-6l17 17");
}

.fodytqh7n {
  d: path("M7.9 4h13.6v13.6m-7.4.4H2.5V6.4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
