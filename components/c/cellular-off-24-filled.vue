<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2ss8s22c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cellular-off-24-filled" /></template>
<style>
.m2ss8s22c {
  fill: currentColor;
  d: path("M3.28 2.22a.75.75 0 1 0-1.06 1.06L11 12.06V19a1 1 0 1 0 2 0v-4.94l2 2v2.945c0 .55.448.995 1 .995s1-.446 1-.995v-.944l3.72 3.72a.75.75 0 0 0 1.06-1.061zM19 15.818l2 2V6a1 1 0 0 0-2 0zm-4-4l2 2V8.995A1 1 0 0 0 16 8c-.552 0-1 .446-1 .995zM8 14c.552 0 1 .445 1 .994v4.012A.997.997 0 0 1 8 20c-.552 0-1-.445-1-.994v-4.012A.997.997 0 0 1 8 14m-4 3c.552 0 1 .44 1 .984v1.032A.99.99 0 0 1 4 20c-.552 0-1-.44-1-.984v-1.032A.99.99 0 0 1 4 17");
}

</style>
