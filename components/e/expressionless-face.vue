<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kr2i49omi"/><path class="lqizd2bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:expressionless-face" /></template>
<style>
.kr2i49omi {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30c16.566 0 30-13.432 30-30S48.566 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.5 16.836 59.5 32S47.163 59.5 32 59.5");
}

.lqizd2bjw {
  fill: currentColor;
  d: path("M40 44H24c-1.504 0-1.504 4 0 4h16c1.504 0 1.504-4 0-4M27.128 28h-16c-1.504 0-1.504 4 0 4h16c1.504 0 1.504-4 0-4m25.744 0h-16c-1.504 0-1.504 4 0 4h16c1.504 0 1.504-4 0-4");
}

</style>
