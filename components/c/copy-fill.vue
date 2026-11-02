<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o592vhasj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-fill" /></template>
<style>
.o592vhasj {
  fill: currentColor;
  d: path("M19 2a3 3 0 0 1 3 3v12a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1H7a1 1 0 0 1 0-2ZM2 9a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
