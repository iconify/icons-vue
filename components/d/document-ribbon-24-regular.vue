<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vddpxv-4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-ribbon-24-regular" /></template>
<style>
.vddpxv-4n {
  fill: currentColor;
  d: path("M18.5 20.002a.5.5 0 0 1-.5.5H9v1.5h9a2 2 0 0 0 2-2V9.83c0-.53-.211-1.04-.586-1.414l-5.829-5.829A2.05 2.05 0 0 0 12.172 2H6a2 2 0 0 0-2 2v7.257a4.5 4.5 0 0 1 1.5-.256v-7a.5.5 0 0 1 .5-.5h6V8a2 2 0 0 0 2 2h4.5zm-5-15.38L17.378 8.5H14a.5.5 0 0 1-.5-.5zM9 15.501a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0m-6 3.742v3.044a.71.71 0 0 0 1.212.503L5.5 21.503l1.288 1.288A.71.71 0 0 0 8 22.288v-3.044a4.5 4.5 0 0 1-2.5.758a4.5 4.5 0 0 1-2.5-.758");
}

</style>
