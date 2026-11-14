<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lagw7xbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:breath-mark" /></template>
<style>
.lagw7xbgz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5c2 0 3.5 1.5 3.5 3.5c0 3.5-2.25 6.25-5.75 7.5l-.5-1q2.625-1.5 3-3C10 12 8.5 10.5 8.5 8.5S10 5 12 5ZM3.5 19.5h17");
}

</style>
