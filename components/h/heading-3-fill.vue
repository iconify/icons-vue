<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpgk-5brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-3-fill" /></template>
<style>
.zpgk-5brr {
  fill: currentColor;
  d: path("M4 5v6h6V5a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0v-6H4v6a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0m11 3h6a1.002 1.002 0 0 1 .707 1.707l-2.483 2.484A4 4 0 0 1 18 20h-3a1 1 0 0 1 0-2h3a2 2 0 1 0 0-4h-1a1.002 1.002 0 0 1-.707-1.707L18.586 10H15a1 1 0 0 1 0-2");
}

</style>
