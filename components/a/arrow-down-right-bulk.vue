<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9afo1r9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-right-bulk" /></template>
<style>
.m9afo1r9g {
  fill: currentColor;
  d: path("M16.999 18H10a1 1 0 0 1 0-2h4.586L6.293 7.707a.999.999 0 1 1 1.414-1.414L16 14.586V10a1 1 0 0 1 2 0v7a1 1 0 0 1-1 1Z");
}

</style>
