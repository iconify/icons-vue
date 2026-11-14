<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lb1dt9blu"/><path class="jhqb5jp-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arcade-cabinet" /></template>
<style>
.jhqb5jp-s {
  d: path("M8.5 5.5h7v5h-7Zm-1 13V17m5.5 1.5h.01m2.99 0h.01");
}

.lb1dt9blu {
  d: path("M6 2.5h12V13l2 2.5v6H4v-6L6 13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
