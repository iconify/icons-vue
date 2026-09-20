<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="o8jxf4xqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-charge-28-regular" /></template>
<style>
.o8jxf4xqj {
  fill: currentColor;
  d: path("M9.407 8.5H5.75a2.25 2.25 0 0 0-2.25 2.25v6.5a2.25 2.25 0 0 0 2.25 2.25h14.5a2.25 2.25 0 0 0 2.25-2.25v-6.5a2.25 2.25 0 0 0-2.25-2.25h-3.164l.27-.544A1.33 1.33 0 0 0 17.448 7h2.802A3.75 3.75 0 0 1 24 10.75V12h1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-1v1.25A3.75 3.75 0 0 1 20.25 21H5.75A3.75 3.75 0 0 1 2 17.25v-6.5A3.75 3.75 0 0 1 5.75 7h4.403zm3.73-5.247c.214-.43.86-.278.861.202v3.55h2.152c.26 0 .43.273.314.506L13.36 13.75c-.214.43-.86.278-.861-.202V9.999h-2.152a.35.35 0 0 1-.314-.506z");
}

</style>
