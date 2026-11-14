<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="shyg3sdzw"/><path class="eojd6r6gr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:functional-group" /></template>
<style>
.eojd6r6gr {
  d: path("M14 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-8 3.5l2 2m3 0l3.75-4");
}

.shyg3sdzw {
  d: path("M2.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm3.5-7a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
