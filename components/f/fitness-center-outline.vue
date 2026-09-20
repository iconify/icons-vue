<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0mw3v4mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fitness-center-outline" /></template>
<style>
.p0mw3v4mb {
  fill: currentColor;
  d: path("M13.4 21.9L12 20.5l3.55-3.55l-8.5-8.5L3.5 12l-1.4-1.4l1.4-1.45l-1.4-1.4l2.1-2.1L2.8 4.2l1.4-1.4l1.45 1.4l2.1-2.1l1.4 1.4l1.45-1.4L12 3.5L8.45 7.05l8.5 8.5L20.5 12l1.4 1.4l-1.4 1.45l1.4 1.4l-2.1 2.1l1.4 1.45l-1.4 1.4l-1.45-1.4l-2.1 2.1l-1.4-1.4z");
}

</style>
