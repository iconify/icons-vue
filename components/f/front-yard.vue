<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lefgaq1-h"/><path class="kibw1zuqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:front-yard" /></template>
<style>
.kibw1zuqs {
  d: path("M6.25 21.5v-5h3.5v5m10.5-9v-3H18.5v1.25h1.75");
}

.lefgaq1-h {
  d: path("M2.5 10L8 4.5l5.5 5.5v11.5h-11ZM16 12.5h5.5v3.75H16Zm2.75 3.75v5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
