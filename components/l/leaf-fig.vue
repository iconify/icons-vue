<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmnf9jbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-fig" /></template>
<style>
.lmnf9jbfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 18.5c-2 1-6 1.5-6.75-1c-.5-2 1.25-3 2.75-3.25c-3 .25-5.25-1.75-5-4.5c.25-2.25 3.5-2.75 5.5-1C8 5.5 9.5 2.5 12 2.5s4 3 3.5 6.25c2-1.75 5.25-1.25 5.5 1c.25 2.75-2 4.75-5 4.5c1.5.25 3.25 1.25 2.75 3.25c-.75 2.5-4.75 2-6.75 1ZM12 7v14.5");
}

</style>
