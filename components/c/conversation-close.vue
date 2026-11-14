<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="moqjqhbix"/><path class="o5fpdqhaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:conversation-close" /></template>
<style>
.moqjqhbix {
  d: path("M5 3.5h14A2.5 2.5 0 0 1 21.5 6v8a2.5 2.5 0 0 1-2.5 2.5H9.5l-4 3.5v-3.5H5A2.5 2.5 0 0 1 2.5 14V6A2.5 2.5 0 0 1 5 3.5Z");
}

.o5fpdqhaz {
  d: path("m8 10.25l3 3l5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
