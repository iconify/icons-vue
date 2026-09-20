<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="sl60hhbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-redo-28-regular" /></template>
<style>
.sl60hhbag {
  fill: currentColor;
  d: path("M7.134 4.655a6.26 6.26 0 0 1 8.028.648l6.27 6.196h-7.679a.75.75 0 0 0 0 1.5h9.5a.75.75 0 0 0 .75-.75V2.75a.75.75 0 0 0-1.5 0v7.7l-6.287-6.214a7.76 7.76 0 0 0-9.951-.804c-3.991 2.838-4.388 8.62-.82 11.975l11.04 10.39a.75.75 0 0 0 1.029-1.093L6.472 14.314c-2.877-2.707-2.558-7.37.662-9.66");
}

</style>
