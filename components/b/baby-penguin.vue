<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jbzxhy2kh"/><path class="j5bipkkgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-penguin" /></template>
<style>
.j5bipkkgt {
  d: path("M12 9c1-1.25 3.25-1.25 3.25 1v4c0 2.25-1.5 3.5-3.25 3.5S8.75 16.25 8.75 14v-4C8.75 7.75 11 7.75 12 9Z");
}

.jbzxhy2kh {
  d: path("M12 3.5c4.25 0 6.5 3.5 6.5 8V14c0 4-2.75 6.5-6.5 6.5S5.5 18 5.5 14v-2.5c0-4.5 2.25-8 6.5-8Zm-6.5 8l-2 3.5m15-3.5l2 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
