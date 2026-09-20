<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gunnayb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-image-24-regular" /></template>
<style>
.gunnayb6j {
  fill: currentColor;
  d: path("M18.75 9A3.25 3.25 0 0 1 22 12.25v6.5A3.25 3.25 0 0 1 18.75 22h-6.5A3.25 3.25 0 0 1 9 18.75v-6.5A3.25 3.25 0 0 1 12.25 9zm-2.543 8.268a1 1 0 0 0-1.414 0l-3.13 3.13q.275.1.587.102h6.5q.31-.002.588-.102zM12.25 10.5a1.75 1.75 0 0 0-1.75 1.75v6.5q.002.31.102.588l3.13-3.131a2.5 2.5 0 0 1 3.536 0l3.13 3.13q.1-.275.102-.587v-6.5a1.75 1.75 0 0 0-1.75-1.75zM9.5 2a7.5 7.5 0 0 1 7.35 6h-1.54A6 6 0 1 0 8 15.31v1.54A7.5 7.5 0 0 1 9.5 2m8.5 9.75a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
