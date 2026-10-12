<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc7vedbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:keyboard-tray-sharp" /></template>
<style>
.rc7vedbkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h18.5v4H2.75zm1.5 4v13m15.5-13v13m-17 0h18.5m-14.5-6.5h10.5v6.5H6.75zM9.25 17h5.5");
}

</style>
