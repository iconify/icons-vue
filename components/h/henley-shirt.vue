<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8sf36bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:henley-shirt" /></template>
<style>
.o8sf36bax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3L4.25 4.75L2.5 15.5h3.25L7 10v11h10V10l1.25 5.5h3.25L19.75 4.75L15.5 3C15 4.75 13.75 5.75 12 5.75S9 4.75 8.5 3ZM12 9h.01M12 12.5h.01");
}

</style>
