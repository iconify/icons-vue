<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czp0lcsor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:filter-fill" /></template>
<style>
.czp0lcsor {
  fill: currentColor;
  d: path("M19 3a2 2 0 0 1 2 2v1c0 .265-.105.52-.293.707L15 12.414V18a1 1 0 0 1-.553.894l-4 2A1 1 0 0 1 9 20v-7.586L3.293 6.707A1 1 0 0 1 3 6V5a2 2 0 0 1 2-2Z");
}

</style>
