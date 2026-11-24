<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke0u_aclj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-warning-corner-fill-round" /></template>
<style>
.ke0u_aclj {
  fill: currentColor;
  d: path("M15.854 4.072A5.005 5.005 0 0 1 20 9a1 1 0 0 1-2 0a3.01 3.01 0 0 0-2.21-2.896A3 3 0 0 1 13 8h-2a3 3 0 0 1-2.79-1.896A3.01 3.01 0 0 0 6 9v8a3 3 0 0 0 3 3a1 1 0 0 1 0 2a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 4 17V9a5.006 5.006 0 0 1 4.146-4.928A3.005 3.005 0 0 1 11 2h2c1.298 0 2.451.838 2.854 2.072M18 14v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m-1 6h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
