<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2_i3hy_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:haze-sharp" /></template>
<style>
.y2_i3hy_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 3a4 4 0 0 0 5.25 5.25A5.5 5.5 0 1 1 12.5 3ZM3.75 17h16.5m-13.5 3.75h10.5");
}

</style>
