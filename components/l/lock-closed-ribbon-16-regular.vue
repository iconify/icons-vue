<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ov7--s9fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-ribbon-16-regular" /></template>
<style>
.ov7--s9fm {
  fill: currentColor;
  d: path("M15 15.5a.5.5 0 0 1-.8.4L13 15l-1.2.9a.5.5 0 0 1-.8-.4v-2.035A4 4 0 0 0 13 14a4 4 0 0 0 2-.535zM8 1a3 3 0 0 1 3 3v2c.292 0 .57.064.82.177A4 4 0 0 0 10.354 7H5a1 1 0 0 0-1 1v5a1 1 0 0 0 1 1h5v1H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2V4a3 3 0 0 1 3-3m5 6a3 3 0 1 1 0 6a3 3 0 0 1 0-6M8 9.5a1 1 0 1 1 0 2a1 1 0 0 1 0-2M8 2a2 2 0 0 0-2 2v2h4V4a2 2 0 0 0-2-2");
}

</style>
