<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpzgwbykl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-end-sharp" /></template>
<style>
.jpzgwbykl {
  fill: currentColor;
  d: path("M19.5 14q-.698 0-1.237-.425t-.698-1.075H2.5v-1h15.066q.159-.65.698-1.075T19.5 10q.839 0 1.42.58T21.5 12t-.58 1.42t-1.42.58");
}

</style>
