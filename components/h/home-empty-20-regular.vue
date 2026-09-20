<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lyjukg-tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-empty-20-regular" /></template>
<style>
.lyjukg-tf {
  fill: currentColor;
  d: path("M8.997 2.385a1.5 1.5 0 0 1 2.006 0l5.5 4.95A1.5 1.5 0 0 1 17 8.45v7.055a1.5 1.5 0 0 1-1.5 1.5h-11a1.5 1.5 0 0 1-1.5-1.5V8.45c0-.425.18-.83.497-1.115zm1.338.743a.5.5 0 0 0-.67 0l-5.5 4.95A.5.5 0 0 0 4 8.45v7.055a.5.5 0 0 0 .5.5h11a.5.5 0 0 0 .5-.5V8.45a.5.5 0 0 0-.165-.372z");
}

</style>
