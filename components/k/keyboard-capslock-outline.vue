<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdhhhubes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-capslock-outline" /></template>
<style>
.cdhhhubes {
  fill: currentColor;
  d: path("M6 18v-2h12v2zm6-12.4l6 6l-1.4 1.4L12 8.4L7.4 13L6 11.6z");
}

</style>
