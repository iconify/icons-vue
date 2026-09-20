<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jozy8mq9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-flow-diagonal-up-right-20-regular" /></template>
<style>
.jozy8mq9a {
  fill: currentColor;
  d: path("M15.854 4.854a.5.5 0 0 0-.708-.708l-7.408 7.409a3 3 0 1 0 .707.707zM4 14a2 2 0 1 1 4 0a2 2 0 0 1-4 0");
}

</style>
