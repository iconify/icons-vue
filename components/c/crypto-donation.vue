<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxj3fdsuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crypto-donation" /></template>
<style>
.lxj3fdsuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5c-4.5-3-9-6-9-9c0-2.25 1.75-4 4.25-4c2 0 3.75 1.25 4.75 2.75c1-1.5 2.75-2.75 4.75-2.75c2.5 0 4.25 1.75 4.25 4c0 3-4.5 6-9 9ZM9.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-.25 9.5h5");
}

</style>
