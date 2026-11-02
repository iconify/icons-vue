<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oay8kys0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:divider-large-bulk-round" /></template>
<style>
.oay8kys0m {
  fill: currentColor;
  d: path("M13 3v18a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0");
}

</style>
