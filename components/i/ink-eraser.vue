<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pswo_q3pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-eraser" /></template>
<style>
.pswo_q3pa {
  fill: currentColor;
  d: path("M17.25 18H22v2h-6.75zm-12.5 2l-2.125-2.125q-.575-.575-.587-1.425T2.6 15l11-11.4q.575-.6 1.413-.6t1.412.575L21.4 8.55q.575.575.575 1.425T21.4 11.4L13 20z");
}

</style>
