<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npvq2hbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-24-filled" /></template>
<style>
.npvq2hbav {
  fill: currentColor;
  d: path("M4 6.25A2.25 2.25 0 0 1 6.25 4h11.5A2.25 2.25 0 0 1 20 6.25v7.5A2.25 2.25 0 0 1 17.75 16H6.25A2.25 2.25 0 0 1 4 13.75zM2.75 17.5a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5z");
}

</style>
