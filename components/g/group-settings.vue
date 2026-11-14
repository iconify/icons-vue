<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g224acb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:group-settings" /></template>
<style>
.g224acb8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c0-2.5 2.1-4.25 4.75-4.25S12 17.5 12 20c0 .6-.4 1-1 1H3.5c-.6 0-1-.4-1-1ZM4 9.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM13 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm.25 6.5c.65-.75 1.45-1.25 2.25-1.25c1.75 0 3.25.5 4.25 1.25m-2.378 3.339l.052-1.038h1.152l.052 1.038l.929.537l.925-.474l.576.997l-.873.564v1.074l.873.564l-.576.997l-.925-.474l-.929.537l-.052 1.038h-1.152l-.052-1.038l-.929-.537l-.925.474l-.576-.997l.873-.564v-1.074l-.873-.564l.576-.997l.925.474Z");
}

</style>
