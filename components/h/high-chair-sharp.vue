<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfvax_ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:high-chair-sharp" /></template>
<style>
.cfvax_ben {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 3.25v9.25m-.75 0h11M11 8.75h9M8.75 12.5L6.5 21.25m8.75-8.75l2.25 8.75M7.46 17.5h9.08");
}

</style>
