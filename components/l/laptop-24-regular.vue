<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7dec1b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-24-regular" /></template>
<style>
.c7dec1b0d {
  fill: currentColor;
  d: path("M6.25 4A2.25 2.25 0 0 0 4 6.25v7.5A2.25 2.25 0 0 0 6.25 16h11.5A2.25 2.25 0 0 0 20 13.75v-7.5A2.25 2.25 0 0 0 17.75 4zM5.5 6.25a.75.75 0 0 1 .75-.75h11.5a.75.75 0 0 1 .75.75v7.5a.75.75 0 0 1-.75.75H6.25a.75.75 0 0 1-.75-.75zM2.75 17.5a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5z");
}

</style>
