<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxlvejbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hexagon-outline" /></template>
<style>
.cxlvejbkh {
  fill: currentColor;
  d: path("M7.089 20.5L2.177 12l4.912-8.5h9.823l4.911 8.5l-4.911 8.5zm.573-1h8.677l4.313-7.5l-4.313-7.5H7.662L3.323 12zM12 12");
}

</style>
