<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xfp5o8bwc"/><ellipse class="r7m55shcr"/><ellipse class="wv7k8sbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aiqfome" /></template>
<style>
.r7m55shcr {
  cx: 13.256px;
  cy: 23.985px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.597px;
  ry: 4.54px;
}

.wv7k8sbhv {
  cx: 28.694px;
  cy: 23.985px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.597px;
  ry: 4.54px;
}

.xfp5o8bwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.058 15.625c-1.546.643-3.964 2.28-6.845-2.346c-3.19 0-6.287-1.434-5.66-5.52c-.516-.236-1.304-1.025-1.553-1.577c-8.756 0-16.564 5.905-17.802 14.835c-1.138 8.211 2.84 16.773 6.377 17.749c1.535.423 3.604-1.752 5.474-1.793c1.545-.034 3.832 2.728 5.61 2.581c1.727-.142 2.622-2.906 5.447-2.602c3.813.412 5.747 5.076 7.785 4.859C40.13 41.465 42 29.272 42 25.99c0-3.61-.25-6.67-1.463-9.309c-1.148 0-1.76-.367-2.48-1.056Z");
}

</style>
