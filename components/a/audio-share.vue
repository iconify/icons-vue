<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ktvzjy3md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audio-share" /></template>
<style>
.ktvzjy3md {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.981 11.74h-8.269c-3.278 0-8.248 3.088-8.212 8.264c.037 5.175 4.71 8.293 8.07 8.293h8.297m4.635-16.557h9.042c5.216 0 7.47 4.549 7.44 8.264m-26.668 0h15.88m4.378 0V36.26m7.926-7.963H27.42");
}

</style>
