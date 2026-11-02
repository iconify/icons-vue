<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bso9a8s_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-medium-fill" /></template>
<style>
.bso9a8s_a {
  fill: currentColor;
  d: path("M5 6h11a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3m2 4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm3 4v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m12-4v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
