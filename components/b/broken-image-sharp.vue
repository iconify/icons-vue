<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbbxjvb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:broken-image-sharp" /></template>
<style>
.kbbxjvb6w {
  fill: currentColor;
  d: path("M3 21v-8.6l3 3l4-4l4 4l4-4l3 3V21zM3 3h18v8.575l-3-3l-4 4l-4-4l-4 4l-3-3z");
}

</style>
