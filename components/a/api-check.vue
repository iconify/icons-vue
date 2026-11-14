<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cq9ic6u3c"/><path class="sago6lk6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-check" /></template>
<style>
.cq9ic6u3c {
  d: path("M11.167 18.339L10 19l-7.5-4.25v-8.5L10 2l7.5 4.25v8.5l-1.287.729");
}

.sago6lk6a {
  d: path("M2.5 6.25L10 10.5l7.5-4.25M10 10.5V19m4.75-1l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
