<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lugh1x25k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-315-48-regular" /></template>
<style>
.lugh1x25k {
  fill: currentColor;
  d: path("M25.328 4.044C35.755 4.728 44 13.4 44 24c0 11.046-8.954 20-20 20S4 35.046 4 24a19.95 19.95 0 0 1 6.395-14.66a1.25 1.25 0 0 1 1.7 1.833A17.45 17.45 0 0 0 6.5 24c0 9.665 7.835 17.5 17.5 17.5S41.5 33.665 41.5 24c0-9.273-7.215-16.863-16.336-17.462a1.25 1.25 0 0 1 .164-2.494M13.776 16.117c-.772-1.489.854-3.114 2.343-2.342l.149.086c3.372 2.149 6.768 4.271 10.052 6.553c.842.585 1.586 1.127 1.923 1.464a4.5 4.5 0 1 1-6.363 6.363c-.337-.337-.879-1.08-1.464-1.923c-1.852-2.665-4.894-7.433-6.553-10.052z");
}

</style>
