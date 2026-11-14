<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s8hy96b8z"/><path class="g3z48d9si"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:input-field-focused" /></template>
<style>
.g3z48d9si {
  d: path("M4.75 7.75h14.5v8.5H4.75Zm3 2.75v3");
}

.s8hy96b8z {
  d: path("M4.25 5h15.5A2.25 2.25 0 0 1 22 7.25v9.5A2.25 2.25 0 0 1 19.75 19H4.25A2.25 2.25 0 0 1 2 16.75v-9.5A2.25 2.25 0 0 1 4.25 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
