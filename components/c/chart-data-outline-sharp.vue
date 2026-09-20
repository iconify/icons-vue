<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgyu3rbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chart-data-outline-sharp" /></template>
<style>
.bgyu3rbcw {
  fill: currentColor;
  d: path("m7.4 15.289l3.05-3.031l2 2l4.05-4.045V12.5h1v-4h-4v1h2.286l-3.336 3.337l-2-2L6.712 14.6zM4 20V4h16v16zm1-1h14V5H5zM5 5v14z");
}

</style>
