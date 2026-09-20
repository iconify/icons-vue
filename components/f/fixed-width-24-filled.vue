<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciclxz4rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:fixed-width-24-filled" /></template>
<style>
.ciclxz4rj {
  fill: currentColor;
  d: path("M3.75 4c.414 0 .75.308.75.688V6h6.75V4.688c0-.38.336-.688.75-.688s.75.308.75.688V6h6.75V4.688c0-.38.336-.688.75-.688s.75.308.75.688v4.125c0 .38-.336.687-.75.687s-.75-.308-.75-.687V7.5h-6.75v1.313c0 .38-.336.687-.75.687s-.75-.308-.75-.687V7.5H4.5v1.313c0 .38-.336.687-.75.687S3 9.192 3 8.813V4.687c0-.38.336-.687.75-.687m2 7A2.75 2.75 0 0 0 3 13.75v4a2.75 2.75 0 0 0 2.75 2.75h5.5V11zm12.5 9.5h-5.5V11h5.5A2.75 2.75 0 0 1 21 13.75v4a2.75 2.75 0 0 1-2.75 2.75");
}

</style>
