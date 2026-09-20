<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfdw9qrpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:highlighter-size-4-rounded" /></template>
<style>
.wfdw9qrpi {
  fill: currentColor;
  d: path("m9.171 20.479l-5.65-5.65q-.165-.165-.165-.366t.165-.367L14.096 3.521q.146-.146.357-.146q.21 0 .35.146l5.676 5.65q.165.165.165.366t-.165.367L9.904 20.479q-.165.165-.366.165t-.367-.165");
}

</style>
