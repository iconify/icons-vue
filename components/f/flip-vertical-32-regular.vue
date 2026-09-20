<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vd0ybybcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-vertical-32-regular" /></template>
<style>
.vd0ybybcs {
  fill: currentColor;
  d: path("M27.54 2.158A1 1 0 0 1 28 3v11a1 1 0 0 1-1 1H3a1 1 0 0 1-.417-1.91l24-11a1 1 0 0 1 .957.068M7.582 13H26V4.558zM28 29a1 1 0 0 1-1.417.91l-24-11A1 1 0 0 1 3 17h24a1 1 0 0 1 1 1z");
}

</style>
