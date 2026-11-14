<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0gm9nbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loose-weight-bag" /></template>
<style>
.b0gm9nbdi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8c-1.25 3-1.5 9.5-.5 12.5H13c1-3 .75-9.5-.25-12.5m-9.5 0H13.5l-.75-3.5c-1.25 1-3-.75-4.25 0s-3-1-4.5 0Zm13.25 7h5v3a2.5 2.5 0 0 1-5 0Zm1 0l-1-5.5");
}

</style>
