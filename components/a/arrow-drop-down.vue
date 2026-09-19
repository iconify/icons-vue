<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep6q_wb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:arrow-drop-down" /></template>
<style>
.ep6q_wb2x {
  fill: currentColor;
  d: path("m7 10l5 5l5-5z");
}

</style>
