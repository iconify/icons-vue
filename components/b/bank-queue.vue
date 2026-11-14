<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s3kvjjbzq"/><path class="ez-fqkb8h"/><path class="y9owrdbvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-queue" /></template>
<style>
.ez-fqkb8h {
  d: path("M8.5 17c0-2.5 1.5-3.5 3.5-3.5s3.5 1 3.5 3.5");
}

.s3kvjjbzq {
  d: path("M3.5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm6 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm6 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-13 10c0-2.5 1.5-3.5 3.5-3.5s3.5 1 3.5 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9owrdbvb {
  d: path("M14.5 17c0-2.5 1.5-3.5 3.5-3.5s3.5 1 3.5 3.5");
}

</style>
