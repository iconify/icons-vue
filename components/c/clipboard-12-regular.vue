<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cxhkqbc8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-12-regular" /></template>
<style>
.cxhkqbc8s {
  fill: currentColor;
  d: path("M4.085 3H3.5a.5.5 0 0 0-.5.5v6a.5.5 0 0 0 .5.5h5a.5.5 0 0 0 .5-.5v-6a.5.5 0 0 0-.5-.5h-.585A1.5 1.5 0 0 1 6.5 4h-1a1.5 1.5 0 0 1-1.415-1m3.83-1H8.5A1.5 1.5 0 0 1 10 3.5v6A1.5 1.5 0 0 1 8.5 11h-5A1.5 1.5 0 0 1 2 9.5v-6A1.5 1.5 0 0 1 3.5 2h.585A1.5 1.5 0 0 1 5.5 1h1a1.5 1.5 0 0 1 1.415 1M5 2.5a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 0-1h-1a.5.5 0 0 0-.5.5");
}

</style>
