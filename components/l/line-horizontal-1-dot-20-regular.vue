<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ry94f7c-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-1-dot-20-regular" /></template>
<style>
.ry94f7c-i {
  fill: currentColor;
  d: path("M3.25 10.75a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m4.5 0a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m4.5 0a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5M18 9.5a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

</style>
