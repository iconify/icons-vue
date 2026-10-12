<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnkhmsb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aries-sharp" /></template>
<style>
.hnkhmsb1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25c0-3-1.75-5-4.25-5s-4 1.75-4 4V11l2 .5M12 9.25c0-3 1.75-5 4.25-5s4 1.75 4 4V11l-2 .5M12 9.25v11");
}

</style>
