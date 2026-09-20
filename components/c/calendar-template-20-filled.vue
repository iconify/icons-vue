<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="myi5kvbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-template-20-filled" /></template>
<style>
.myi5kvbei {
  fill: currentColor;
  d: path("M5 2a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h2.035A3.5 3.5 0 0 1 7 15.5v-5c0-.98.402-1.865 1.05-2.5H5.5a.5.5 0 0 1 0-1h10q.255 0 .5.035V5a3 3 0 0 0-3-3zm0 3.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1-.5-.5m3 5A2.5 2.5 0 0 1 10.5 8h5a2.5 2.5 0 0 1 2.5 2.5v.5H8zm0 5V12h10v3.5a2.5 2.5 0 0 1-2.5 2.5h-5A2.5 2.5 0 0 1 8 15.5");
}

</style>
