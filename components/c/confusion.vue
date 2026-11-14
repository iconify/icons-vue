<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ocyf5ip6z"/><path class="e30fyq5fp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:confusion" /></template>
<style>
.e30fyq5fp {
  d: path("M8.75 10.5c-.5-2.5 2.5-3.75 4-2.25c1.25 1.25-.5 3.5-2 2.5C9.5 10 10.5 7 13.25 7.25C15.5 7.5 16 10.5 14.75 12s-4.5 1.25-5.25 0M9 15c1.5-.5 3 .25 4-.5M16.5 9h.01");
}

.ocyf5ip6z {
  d: path("M8 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7C4.5 6.25 7.75 3 12 3c4 0 7 2.75 7 6.75l1.5 3.5c.25.5-.1 1-.75 1H19v2.25c0 1.1-.9 2-2 2h-2v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
