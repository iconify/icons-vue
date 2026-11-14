<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e58c8tbju"/><path class="h0jk5d60c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coconut-offering" /></template>
<style>
.e58c8tbju {
  d: path("M5 11a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

.h0jk5d60c {
  d: path("M3 18h18c-1 1.75-2.5 2.5-4.5 2.5h-9c-2 0-3.5-.75-4.5-2.5Zm7.5-10.25h.01m2.99 0h.01M12 10.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
