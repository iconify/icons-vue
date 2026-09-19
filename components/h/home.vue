<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2ky_fbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:home" /></template>
<style>
.i2ky_fbxv {
  fill: currentColor;
  d: path("M10 20v-6h4v6h5v-8h3L12 3L2 12h3v8z");
}

</style>
