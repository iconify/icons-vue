<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb235eb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-network-cell" /></template>
<style>
.gb235eb5s {
  fill: currentColor;
  d: path("M2 22h20V2zm18-2h-3V9.83l3-3z");
}

</style>
