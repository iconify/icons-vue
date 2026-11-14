<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dutgie71m"/><path class="t6-u3v5du"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:getting-started" /></template>
<style>
.dutgie71m {
  d: path("M12 2.5c3.5 2.25 4.5 6 4 12.5H8c-.5-6.5.5-10.25 4-12.5Z");
}

.t6-u3v5du {
  d: path("m8.25 10.5l-2.75 3v3L8 15m7.75-4.5l2.75 3v3L16 15m-5.25 0L12 18.25L13.25 15M4.5 21h15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
