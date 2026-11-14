<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x77l4bcoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-lamp-reptile" /></template>
<style>
.x77l4bcoo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v2M7 10l2.5-5.5h5L17 10Zm7 0a2 2 0 0 1-4 0m-7.5 8.25c3-.25 5-2.5 8-2.5H16c2.5 0 4 .75 5.5 1.75c-1.5 1-3 1.5-5.5 1.5h-5.5c-2.5 0-4.5-.5-8-.75Zm8 .75l-.75 2M16 19l.75 2");
}

</style>
