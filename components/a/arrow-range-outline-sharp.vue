<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd1ydpbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-range-outline-sharp" /></template>
<style>
.wd1ydpbbv {
  fill: currentColor;
  d: path("m7 17l-5-5l5-5l1.4 1.4L5.825 11h12.35L15.6 8.4L17 7l5 5l-5 5l-1.4-1.4l2.575-2.6H5.825L8.4 15.6z");
}

</style>
