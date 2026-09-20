<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch7wnrarh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:free-cancellation-sharp" /></template>
<style>
.ch7wnrarh {
  fill: currentColor;
  d: path("M16.55 22.5L13 18.95l1.4-1.4l2.125 2.125l4.25-4.25l1.4 1.425zM7.4 17L6 15.6L7.6 14L6 12.4L7.4 11L9 12.6l1.6-1.6l1.4 1.4l-1.6 1.6l1.6 1.6l-1.4 1.4L9 15.4zM3 22V4h3V2h2v2h8V2h2v2h3v8.35l-2 2.025V10H5v10h6.25l1.975 2z");
}

</style>
