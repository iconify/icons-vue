<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yaf4l_bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-text-20-regular" /></template>
<style>
.yaf4l_bzr {
  fill: currentColor;
  d: path("M2.5 5a.5.5 0 0 0 0 1H8a.5.5 0 0 0 0-1zm3 3a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zM4 11.5a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1h-10a.5.5 0 0 1-.5-.5M2.5 14a.5.5 0 0 0 0 1H11a.5.5 0 0 0 0-1zm10-5.5A.5.5 0 0 1 13 8h3.5a.5.5 0 0 1 0 1H13a.5.5 0 0 1-.5-.5m-2-3.5a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1z");
}

</style>
