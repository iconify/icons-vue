<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="grri4hb6u"/><path class="jsdrrsbjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dna-check" /></template>
<style>
.grri4hb6u {
  d: path("M4 2.5c0 4.75 9 5.25 9 9.5s-9 4.75-9 9.5");
}

.jsdrrsbjm {
  d: path("M13 2.5c0 4.75-9 5.25-9 9.5c0 2.907 4.211 4.06 6.872 6.018m1.546 1.549c.366.562.582 1.196.582 1.933m-8.5-17h8M4 12h9m-8.5 7.5h7.8m2.45-1.5l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
