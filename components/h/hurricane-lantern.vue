<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nuygbdb3o"/><path class="dmex28lms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hurricane-lantern" /></template>
<style>
.dmex28lms {
  d: path("M8 9h8l-1.5-2h-5Zm.5 0c-2 2.5-2 6.5 0 9h7c2-2.5 2-6.5 0-9m-9 9h11v3.5h-11Zm3.25-9v9m4.5-9v9");
}

.nuygbdb3o {
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
