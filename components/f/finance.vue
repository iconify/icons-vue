<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_lxmcbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:finance" /></template>
<style>
.r_lxmcbhh {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V3h2v16h16v2zm1-3V9h4v9zm5 0V4h4v14zm5 0v-5h4v5z");
}

</style>
