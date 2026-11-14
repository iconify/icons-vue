<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwztt3s_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ball-bouncing" /></template>
<style>
.pwztt3s_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 8.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM3 5.5c1.5 6.5 2.5 13 4 13c1.25 0 2-2 3-4.5m-7 7.5h18");
}

</style>
