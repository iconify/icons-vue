<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h4nbuseey"/><path class="e-wgz24fe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:affiliate-link" /></template>
<style>
.e-wgz24fe {
  d: path("M19 16.75c-.25-.5-.75-.75-1.25-.75c-.75 0-1.25.5-1.25 1c0 1.5 2.5.75 2.5 2c0 .5-.5 1-1.25 1s-1.25-.25-1.25-.75");
}

.h4nbuseey {
  d: path("M9.616 16.334a3.5 3.5 0 0 1-4.95-4.95m0 0l2.122-2.121m0 0a3.5 3.5 0 0 1 5.863 1.598m-3.035 5.473l1.979-1.98m1.503-1.867q-.269.113-.553.18q-.284.068-.575.087q-.291.02-.581-.009q-.291-.03-.572-.106q-.222-.061-.435-.15q-.212-.089-.411-.205q-.199-.117-.381-.258t-.343-.305q-.162-.164-.301-.348t-.253-.384q-.113-.2-.2-.414q-.086-.213-.144-.436m.914-3.351l2.121-2.122m0 0a3.5 3.5 0 0 1 4.95 4.95m-1.981 1.98l1.981-1.98M13.5 17.75a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
