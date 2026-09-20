<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoke65b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-thickness-24-regular" /></template>
<style>
.eoke65b4l {
  fill: currentColor;
  d: path("M2.75 3.5a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5zM2 10.75c0-.69.56-1.25 1.25-1.25h17.5a1.25 1.25 0 1 1 0 2.5H3.25C2.56 12 2 11.44 2 10.75m0 7.5c0-.966.784-1.75 1.75-1.75h16.5a1.75 1.75 0 1 1 0 3.5H3.75A1.75 1.75 0 0 1 2 18.25");
}

</style>
