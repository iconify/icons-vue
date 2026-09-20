<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y2wqu0b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-exit-12-filled" /></template>
<style>
.y2wqu0b3d {
  fill: currentColor;
  d: path("M3 3.75A.75.75 0 0 1 3.75 3h3a.75.75 0 0 0 0-1.5h-3A2.25 2.25 0 0 0 1.5 3.75v4.5a2.25 2.25 0 0 0 2.25 2.25h3a.75.75 0 0 0 0-1.5h-3A.75.75 0 0 1 3 8.25zm5.78-.28a.75.75 0 0 0-1.06 1.06l.72.72H5.25a.75.75 0 0 0 0 1.5h3.19l-.72.72a.75.75 0 0 0 1.06 1.06l2-2a.75.75 0 0 0 0-1.06z");
}

</style>
