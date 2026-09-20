<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmdkduzew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:area-chart-outline-sharp" /></template>
<style>
.cmdkduzew {
  fill: currentColor;
  d: path("M4 19V9l3.23 2.423l4.962-6.98L16.654 8H20v11zm4-2l4-5.5l7 5.45V9h-2.7l-3.9-3.125l-4.95 6.95L5 11v3.6z");
}

</style>
