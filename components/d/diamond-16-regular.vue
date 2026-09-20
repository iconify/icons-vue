<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="if-zng0ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-16-regular" /></template>
<style>
.if-zng0ff {
  fill: currentColor;
  d: path("M6.232 1.232a2.5 2.5 0 0 1 3.536 0l4.999 5c.976.976.976 2.56 0 3.536l-5 4.999a2.5 2.5 0 0 1-3.535 0l-5-5a2.5 2.5 0 0 1 0-3.536zm2.829.707a1.5 1.5 0 0 0-2.122 0l-5 5a1.5 1.5 0 0 0 0 2.122l5 4.999a1.5 1.5 0 0 0 2.122 0l4.999-5a1.5 1.5 0 0 0 0-2.121z");
}

</style>
