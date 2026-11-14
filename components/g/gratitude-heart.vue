<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv0o5ugto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gratitude-heart" /></template>
<style>
.rv0o5ugto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12.5c-3-2.5-5.25-4-5.25-6.25A2.75 2.75 0 0 1 12 4.75a2.75 2.75 0 0 1 5.25 1.5C17.25 8.5 15 10 12 12.5Zm-9.5-3c0 5 3.5 8 9.5 8m9.5-8c0 5-3.5 8-9.5 8m-4-.25v4.25m8-4.25v4.25");
}

</style>
