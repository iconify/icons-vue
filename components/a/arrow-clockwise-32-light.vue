<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v2qd10b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-clockwise-32-light" /></template>
<style>
.v2qd10b3z {
  fill: currentColor;
  d: path("M4 16C4 9.373 9.373 4 16 4c4.015 0 7.57 1.972 9.748 5H20.5a.5.5 0 0 0 0 1h6a.5.5 0 0 0 .5-.5v-6a.5.5 0 0 0-1 0v4.193A12.97 12.97 0 0 0 16 3C8.82 3 3 8.82 3 16s5.82 13 13 13s13-5.82 13-13q0-.801-.095-1.578a.484.484 0 0 0-.484-.422a.516.516 0 0 0-.504.581Q28 15.28 28 16c0 6.627-5.373 12-12 12S4 22.627 4 16");
}

</style>
