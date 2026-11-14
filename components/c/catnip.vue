<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa0mpacpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:catnip" /></template>
<style>
.qa0mpacpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.5v12m0-12c-3-2-2.5-5 0-7c2.5 2 3 5 0 7Zm0 5.5c-2.5-4-6-4.5-8.5-3.5c1.5 3.5 5 5 8.5 3.5Zm0 0c2.5-4 6-4.5 8.5-3.5c-1.5 3.5-5 5-8.5 3.5Z");
}

</style>
