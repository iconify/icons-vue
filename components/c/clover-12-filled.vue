<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b2s5job3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clover-12-filled" /></template>
<style>
.b2s5job3u {
  fill: currentColor;
  d: path("M4.5 6a.5.5 0 0 1 .5.5V8a2 2 0 1 1-2-2zM8 6a2 2 0 1 1-2 2V6.5a.5.5 0 0 1 .5-.5zM3 1a2 2 0 0 1 2 2v1.5a.5.5 0 0 1-.5.5H3a2 2 0 1 1 0-4m5 0a2 2 0 1 1 0 4H6.5a.5.5 0 0 1-.5-.5V3a2 2 0 0 1 2-2");
}

</style>
