<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8z_y1k4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-right-24-regular" /></template>
<style>
.z8z_y1k4v {
  fill: currentColor;
  d: path("M13.267 4.209a.75.75 0 0 0-1.034 1.086l6.251 5.955H3.75a.75.75 0 0 0 0 1.5h14.734l-6.251 5.954a.75.75 0 0 0 1.034 1.087l7.42-7.067a1 1 0 0 0 .3-.58a.8.8 0 0 0-.001-.29a1 1 0 0 0-.3-.578z");
}

</style>
