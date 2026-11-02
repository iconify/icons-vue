<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb6lnqq6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-empty-fill" /></template>
<style>
.gb6lnqq6r {
  fill: currentColor;
  d: path("M2 9a3 3 0 0 1 3-3h11a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm20 5a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>
