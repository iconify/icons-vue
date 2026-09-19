<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7mxlrb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:filter-7" /></template>
<style>
.o7mxlrb0h {
  fill: currentColor;
  d: path("M3 5H1v16c0 1.1.9 2 2 2h16v-2H3zm18-4H7c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 16H7V3h14zm-8-2l4-8V5h-6v2h4l-4 8z");
}

</style>
