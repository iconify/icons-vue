<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aikwr8n5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-arrow-upward" /></template>
<style>
.aikwr8n5r {
  fill: currentColor;
  d: path("m4 12l1.41 1.41L11 7.83V20h2V7.83l5.58 5.59L20 12l-8-8z");
}

</style>
