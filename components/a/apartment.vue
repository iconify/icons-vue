<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz164qyhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:apartment" /></template>
<style>
.jz164qyhc {
  fill: currentColor;
  d: path("M3 21V7h4V3h10v8h4v10h-8v-4h-2v4zm2-2h2v-2H5zm0-4h2v-2H5zm0-4h2V9H5zm4 4h2v-2H9zm0-4h2V9H9zm0-4h2V5H9zm4 8h2v-2h-2zm0-4h2V9h-2zm0-4h2V5h-2zm4 12h2v-2h-2zm0-4h2v-2h-2z");
}

</style>
