<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="buin2vx_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-clock-20-regular" /></template>
<style>
.buin2vx_s {
  fill: currentColor;
  d: path("M19 5.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0M14.5 3a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H16a.5.5 0 0 0 0-1h-1V3.5a.5.5 0 0 0-.5-.5M17 16v-5.6a5.5 5.5 0 0 0 1-.657V16a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h5.022q.047.516.185 1H4a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h5.5V7.794a5.5 5.5 0 0 0 1 1.48V17H16a1 1 0 0 0 1-1m-11-.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1-.5-.5m6.5-.5a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1z");
}

</style>
