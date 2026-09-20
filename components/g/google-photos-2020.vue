<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kwv-sky3u"/><path class="mun7k9bos"/><path class="yqtf-wbdb"/><path class="y4m1ju25n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-photos-2020" /></template>
<style>
.kwv-sky3u {
  fill: var(--svg-color--fbbb05, #fbbb05);
  d: path("M64 58.149c35.328 0 64 28.672 64 64V128H5.851C2.633 128 0 125.367 0 122.149c0-35.328 28.672-64 64-64");
}

.mun7k9bos {
  fill: var(--svg-color--e94335, #e94335);
  d: path("M197.851 64c0 35.328-28.672 64-64 64H128V5.851C128 2.633 130.633 0 133.851 0c35.328 0 64 28.672 64 64");
}

.y4m1ju25n {
  fill: var(--svg-color--0f9d58, #0f9d58);
  d: path("M58.149 192c0-35.328 28.672-64 64-64H128v122.149c0 3.218-2.633 5.851-5.851 5.851c-35.328 0-64-28.672-64-64");
}

.yqtf-wbdb {
  fill: var(--svg-color--4285f4, #4285f4);
  d: path("M192 197.851c-35.328 0-64-28.672-64-64V128h122.149c3.218 0 5.851 2.633 5.851 5.851c0 35.328-28.672 64-64 64");
}

</style>
