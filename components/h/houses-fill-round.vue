<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz8meba1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:houses-fill-round" /></template>
<style>
.gz8meba1h {
  fill: currentColor;
  d: path("M8 9.248V3a1 1 0 0 1 1-1h8a5 5 0 0 1 5 5v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-5.81a5 5 0 0 1 1.707-3.763l1.134-.992A4.8 4.8 0 0 1 8 9.248M20 7a3 3 0 0 0-3-3h-7v5.684a4.8 4.8 0 0 1 1.159.751l1.134.992A5 5 0 0 1 14 15.19V20h6Zm-7-1h.01a1 1 0 0 1 0 2H13a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2m0 4h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2m0 4h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
