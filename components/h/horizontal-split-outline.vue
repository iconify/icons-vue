<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drdne8bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:horizontal-split-outline" /></template>
<style>
.drdne8bss {
  fill: currentColor;
  d: path("M4 18v-6h16v6zm0-8V9h16v1zm0-3V6h16v1z");
}

</style>
