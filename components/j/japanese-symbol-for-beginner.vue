<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i7gqwabog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:japanese-symbol-for-beginner" /></template>
<style>
.i7gqwabog {
  fill: currentColor;
  d: path("M52.117 2.118a1.49 1.49 0 0 0-1.585.269L32 19.328L13.467 2.387a1.49 1.49 0 0 0-1.584-.269A1.43 1.43 0 0 0 11 3.429v39.285c0 .396.167.772.463 1.043l19.535 17.856A1.48 1.48 0 0 0 32 62c.359 0 .72-.129 1.002-.387l19.535-17.856c.295-.271.463-.648.463-1.043V3.429a1.43 1.43 0 0 0-.883-1.311M13.93 42.096V6.726l17.068 15.603c.007.007.018.009.025.016v35.377zm36.139 0L32.977 57.721V22.344c.008-.007.018-.009.025-.016L50.069 6.726z");
}

</style>
