<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tvyk14bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:live-off-16-filled" /></template>
<style>
.tvyk14bdj {
  fill: currentColor;
  d: path("M1.147 1.315a.5.5 0 0 1 .707 0l13 13a.5.5 0 0 1-.707.708L8.113 8.989Q8.058 9 8 9a1 1 0 0 1-1-1q.001-.059.01-.114L5.853 6.729a2.5 2.5 0 0 0 .382 3.039a.75.75 0 0 1-1.06 1.06a4 4 0 0 1-.405-5.182L3.698 4.574a5.5 5.5 0 0 0 .412 7.315a.75.75 0 0 1-1.06 1.06a7 7 0 0 1-.417-9.44L1.147 2.022a.5.5 0 0 1 0-.707M11.889 3.05a.75.75 0 0 1 1.06 0a7 7 0 0 1 .878 8.825l-1.087-1.087a5.5 5.5 0 0 0-.851-6.677a.75.75 0 0 1 0-1.061M9.77 5.172a.75.75 0 0 1 1.06 0a4 4 0 0 1 .802 4.509L10.45 8.499a2.5 2.5 0 0 0-.68-2.267a.75.75 0 0 1 0-1.06");
}

</style>
