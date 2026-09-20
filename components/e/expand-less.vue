<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzy5p-bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:expand-less" /></template>
<style>
.uzy5p-bcz {
  fill: currentColor;
  d: path("m7.4 14.702l-.708-.708L12 8.687l5.308 5.307l-.708.708l-4.6-4.6z");
}

</style>
