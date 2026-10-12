<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju2bpwe1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heating-pad-sharp" /></template>
<style>
.ju2bpwe1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.5H15.5v11.75H2.75zm0 4H15.5M2.75 17.25H15.5m0-1.75H18m0-3h3.25v6.25H18zM5.75 2.75L4.625 3.875L5.75 5l1.125 1.125L5.75 7.25m3.75-4.5L8.375 3.875L9.5 5l1.125 1.125L9.5 7.25m3.75-4.5l-1.125 1.125L13.25 5l1.125 1.125L13.25 7.25");
}

</style>
