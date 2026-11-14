<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ohmm7ghkt"/><path class="bjp3m-b6a"/><path class="y8_iddcar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cart-clock" /></template>
<style>
.bjp3m-b6a {
  d: path("M2.5 3.5h2L7 15m0 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8-1a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ohmm7ghkt {
  d: path("M5.25 7H20.5l-1.25 5.25h-7V15H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y8_iddcar {
  d: path("M18 16.75V18l1 1");
}

</style>
