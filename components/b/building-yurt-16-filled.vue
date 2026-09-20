<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vfosjgb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:building-yurt-16-filled" /></template>
<style>
.vfosjgb0n {
  fill: currentColor;
  d: path("M15 12.25A1.75 1.75 0 0 1 13.25 14H10.5A1.5 1.5 0 0 1 9 12.5v-2a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v2A1.5 1.5 0 0 1 5.5 14H2.75A1.75 1.75 0 0 1 1 12.25V7.83c.228.108.481.171.75.171h12.5c.269 0 .522-.063.75-.171zM7.136 2.226a1.75 1.75 0 0 1 1.728 0l5.25 2.98c.461.262.772.716.86 1.23A.75.75 0 0 1 14.25 7H1.75a.75.75 0 0 1-.725-.566c.088-.513.4-.967.86-1.228z");
}

</style>
