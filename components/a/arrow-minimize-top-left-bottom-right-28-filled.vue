<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="c_7n4vbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-minimize-top-left-bottom-right-28-filled" /></template>
<style>
.c_7n4vbio {
  fill: currentColor;
  d: path("m24 15l.116.007A1 1 0 0 1 25 16l-.007.116A1 1 0 0 1 24 17h-5.585l7.292 7.293l.083.094a1 1 0 0 1-1.497 1.32L17 18.413V24l-.007.116A1 1 0 0 1 15 24v-8l.007-.116A1 1 0 0 1 16 15zM2.293 2.293a1 1 0 0 1 1.414 0L11 9.585V4l.007-.116A1 1 0 0 1 13 4v8l-.007.116A1 1 0 0 1 12 13H4l-.117-.007A1 1 0 0 1 3 12l.007-.116A1 1 0 0 1 4 11h5.587L2.293 3.707l-.083-.094a1 1 0 0 1 .083-1.32");
}

</style>
