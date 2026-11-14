<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uuezpkzhr"/><path class="frtykac3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:employee-birthday" /></template>
<style>
.frtykac3b {
  d: path("M4.5 15.5c2.5 2 3.5-2 7.5 0s5-2 7.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuezpkzhr {
  d: path("M4.5 11h15v9.5h-15Zm7.5 0V8m0 0c-1.5-1.5-.75-3.5 0-4.5c.75 1 1.5 3 0 4.5");
}

</style>
