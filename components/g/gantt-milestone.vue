<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi3uidvkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gantt-milestone" /></template>
<style>
.gi3uidvkh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5H11v4.5H2.5ZM7 15h14.5v4.5H7ZM17.5 3.75l3.5 3.5l-3.5 3.5l-3.5-3.5Z");
}

</style>
