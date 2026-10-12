<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxfimxb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fair-trade-sharp" /></template>
<style>
.jxfimxb8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5v13.75m-3.5 0h7m-10.75-13h14.5m-14.5 0l-2 5.25m2-5.25l2 5.25m12.5-5.25l-2 5.25m2-5.25l2 5.25m-18.5 0h4v2h-4zm14.5 0h4v2h-4zM12 6.25c0-2 1.25-3.25 3.5-3.5c0 2-1.25 3.25-3.5 3.5Z");
}

</style>
