<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uavjzkako"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-eraser-off" /></template>
<style>
.uavjzkako {
  fill: currentColor;
  d: path("M19.775 22.625L15.05 17.9L13 20H4.75l-2.125-2.125q-.575-.575-.587-1.425T2.6 15l4.7-4.85l-5.925-5.925L2.8 2.8l18.4 18.4zm-1.9-7.6L10.1 7.25l3.5-3.65q.575-.6 1.413-.6t1.412.575L21.4 8.55q.575.575.575 1.425T21.4 11.4z");
}

</style>
