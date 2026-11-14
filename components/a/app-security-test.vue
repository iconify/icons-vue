<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh_d_eb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:app-security-test" /></template>
<style>
.xh_d_eb6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.7 21.5H3v-19h10v18.4M6.5 5.5h3m-3 13h3m7.25-5h4m-3 0v3.25l-2 4.75h6l-2-4.75V13.5");
}

</style>
