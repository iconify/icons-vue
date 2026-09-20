<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uquu8b0xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-markdown-16-filled" /></template>
<style>
.uquu8b0xn {
  fill: currentColor;
  d: path("M5.615 10.014A.5.5 0 0 1 6 10.5v4a.5.5 0 0 1-1 0v-1.882l-1.053 2.106a.5.5 0 0 1-.894 0L2 12.618V14.5a.5.5 0 0 1-1 0v-4a.5.5 0 0 1 .947-.224L3.5 13.382l1.553-3.106a.5.5 0 0 1 .562-.262M9 10a.5.5 0 0 1 .5.5v2.793l.646-.646a.5.5 0 1 1 .707.707l-1.5 1.5a.5.5 0 0 1-.113.082a.5.5 0 0 1-.339.054a.5.5 0 0 1-.142-.055a.5.5 0 0 1-.113-.082l-1.5-1.5a.5.5 0 0 1 0-.707a.5.5 0 0 1 .708 0l.646.647V10.5A.5.5 0 0 1 9 10M8 4.5A1.5 1.5 0 0 0 9.5 6H13v7.5a1.5 1.5 0 0 1-1.5 1.5h-.879l.94-.94a1.5 1.5 0 0 0 .103-2.006l-.104-.114l-.114-.104a1.5 1.5 0 0 0-.946-.336v-1a1.5 1.5 0 0 0-3 0v1q-.257 0-.5.085V10.5a1.5 1.5 0 0 0-1.031-1.425l-.124-.035l-.127-.024a1.5 1.5 0 0 0-1.497.7l-.063.113l-.658 1.316l-.5-1V2.5A1.5 1.5 0 0 1 4.5 1H8zm4.75.5H9.5a.5.5 0 0 1-.5-.5V1.25z");
}

</style>
