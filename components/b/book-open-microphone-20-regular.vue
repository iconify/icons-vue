<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zq8phacqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-microphone-20-regular" /></template>
<style>
.zq8phacqd {
  fill: currentColor;
  d: path("M18.5 13.5a.5.5 0 0 1 .5.5a4 4 0 0 1-3.5 3.968v.532a.5.5 0 0 1-1 0v-.532A4 4 0 0 1 11 14a.5.5 0 0 1 1 0a3 3 0 1 0 6 0a.5.5 0 0 1 .5-.5M8 3c.818 0 1.544.393 2 1c.456-.607 1.182-1 2-1h4.5A1.5 1.5 0 0 1 18 4.5V12a3 3 0 0 0-1-2.232V4.5a.5.5 0 0 0-.5-.5H12a1.5 1.5 0 0 0-1.5 1.5v7.384c-.306.274-.5.672-.5 1.116c0 .986.285 1.906.778 2.68A2.5 2.5 0 0 1 10 16c-.456.607-1.182 1-2 1H3.5A1.5 1.5 0 0 1 2 15.5v-11A1.5 1.5 0 0 1 3.5 3zM3.5 4a.5.5 0 0 0-.5.5v11a.5.5 0 0 0 .5.5H8a1.5 1.5 0 0 0 1.5-1.5v-9A1.5 1.5 0 0 0 8 4zM15 10a2 2 0 0 1 2 2v2a2 2 0 1 1-4 0v-2a2 2 0 0 1 2-2");
}

</style>
