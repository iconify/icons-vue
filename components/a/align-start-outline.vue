<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax2hqfbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-start-outline" /></template>
<style>
.ax2hqfbxb {
  fill: currentColor;
  d: path("M2 4V2h20v2zm5 6V7h10v3zm0 6v-3h10v3z");
}

</style>
