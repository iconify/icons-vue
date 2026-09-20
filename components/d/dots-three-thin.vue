<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bwdbz5bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:dots-three-thin" /></template>
<style>
.bwdbz5bas {
  fill: currentColor;
  d: path("M136 128a8 8 0 1 1-8-8a8 8 0 0 1 8 8m-76-8a8 8 0 1 0 8 8a8 8 0 0 0-8-8m136 0a8 8 0 1 0 8 8a8 8 0 0 0-8-8");
}

</style>
