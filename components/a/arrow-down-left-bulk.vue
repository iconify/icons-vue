<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7-8rccxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-left-bulk" /></template>
<style>
.e7-8rccxv {
  fill: currentColor;
  d: path("M6 17v-7a1 1 0 0 1 2 0v4.586l8.293-8.293a.999.999 0 1 1 1.414 1.414L9.414 16H14a1 1 0 0 1 0 2H7a1 1 0 0 1-1-1");
}

</style>
