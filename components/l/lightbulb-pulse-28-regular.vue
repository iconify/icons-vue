<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="y1gw0mbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lightbulb-pulse-28-regular" /></template>
<style>
.y1gw0mbff {
  fill: currentColor;
  d: path("M7.367 14.5c.455.86 1.07 1.62 1.808 2.242c.572.482 1.078 1.138 1.274 1.956L10.762 20h6.476l.313-1.302c.196-.818.702-1.474 1.274-1.956a7.5 7.5 0 0 0 1.808-2.242h1.659a9 9 0 0 1-2.501 3.39c-.403.339-.68.736-.781 1.158l-1.07 4.46A3.25 3.25 0 0 1 14.78 26h-1.56a3.25 3.25 0 0 1-3.16-2.492l-1.07-4.46c-.101-.422-.378-.82-.781-1.158a9 9 0 0 1-2.501-3.39zm4.153 8.658a1.75 1.75 0 0 0 1.7 1.342h1.56a1.75 1.75 0 0 0 1.7-1.342l.399-1.658H11.12zM11.01 6.5a.75.75 0 0 1 .702.513l2.375 7.127l2.224-5.186a.75.75 0 0 1 1.34-.076L19.436 12h3.314a.75.75 0 0 1 0 1.5H19a.75.75 0 0 1-.651-.378l-1.253-2.192l-2.406 5.616a.75.75 0 0 1-1.402-.059l-2.32-6.958l-1.263 3.477A.75.75 0 0 1 9 13.5H5.25a.75.75 0 0 1 0-1.5h3.225l1.82-5.006a.75.75 0 0 1 .715-.494M14 2a9 9 0 0 1 9 9h-1.5a7.5 7.5 0 0 0-15 0H5a9 9 0 0 1 9-9");
}

</style>
