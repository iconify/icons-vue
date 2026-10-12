<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxa0w6abn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:caulk-gun-sharp" /></template>
<style>
.wxa0w6abn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 5h10.5v4.5H7.75zm0 1.25L3 7v1l4.75.75m10.5-1.5h3m0-2.5v5m-4.5-.25L18 18.75M14 9.5l-1.25 5.75");
}

</style>
