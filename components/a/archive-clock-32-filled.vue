<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="wuzmyacmq"/><path class="am4pywbyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-clock-32-filled" /></template>
<style>
.am4pywbyr {
  d: path("M28 15.516A8.96 8.96 0 0 0 23 14c-1.093 0-2.14.194-3.108.55A1 1 0 0 0 19 14h-6a1 1 0 1 0 0 2h4.345A8.98 8.98 0 0 0 14 23c0 2.305.867 4.408 2.293 6H9.5A5.5 5.5 0 0 1 4 23.5V11h24zM27 3a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.wuzmyacmq {
  d: path("M23 30.5a7.5 7.5 0 1 1 0-15a7.5 7.5 0 0 1 0 15M22.75 18a.75.75 0 0 0-.75.75v4.5c0 .414.336.75.75.75h3.5a.75.75 0 0 0 0-1.5H23.5v-3.75a.75.75 0 0 0-.75-.75");
}

</style>
