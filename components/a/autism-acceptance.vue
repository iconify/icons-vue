<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp59dlb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:autism-acceptance" /></template>
<style>
.tp59dlb5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c-2.5-3.5-8-4-8 0s5.5 3.5 8 0s8-4 8 0s-5.5 3.5-8 0Zm0 8.5s-2-1.25-2-2.5c0-.5.5-1 1-1s.75.25 1 .5c.25-.25.5-.5 1-.5s1 .5 1 1c0 1.25-2 2.5-2 2.5Z");
}

</style>
