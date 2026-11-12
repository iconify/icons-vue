<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d5ilpc3xf"/><path class="q1otv9jnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ladle-broken" /></template>
<style>
.d5ilpc3xf {
  d: path("M22 14.5V15.6842C22 19.1723 19.1723 22 15.6842 22C12.1961 22 9.36842 19.1723 9.36842 15.6842V14.6316V9.1579M9.36842 5.68421C9.36842 3.64948 7.71894 2 5.68421 2C3.64948 2 2 3.64948 2 5.68421");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q1otv9jnf {
  d: path("M16 12C12.9461 12 9.5 13.1193 9.5 14.5C9.5 15.8807 12.9461 17 16 17C19.0539 17 22 15.8807 22 14.5C22 13.7802 21.1993 13.1314 20 12.6753");
}

</style>
