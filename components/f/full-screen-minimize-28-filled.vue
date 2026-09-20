<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="b3i3y1bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:full-screen-minimize-28-filled" /></template>
<style>
.b3i3y1bhk {
  fill: currentColor;
  d: path("M9 2.5a1 1 0 0 1 1 1V7a3 3 0 0 1-3 3H3.5a1 1 0 0 1 0-2H7a1 1 0 0 0 1-1V3.5a1 1 0 0 1 1-1m10 0a1 1 0 0 1 1 1V7a1 1 0 0 0 1 1h3.5a1 1 0 1 1 0 2H21a3 3 0 0 1-3-3V3.5a1 1 0 0 1 1-1M2.5 19a1 1 0 0 1 1-1H7a3 3 0 0 1 3 3v3.5a1 1 0 1 1-2 0V21a1 1 0 0 0-1-1H3.5a1 1 0 0 1-1-1M18 21a3 3 0 0 1 3-3h3.5a1 1 0 1 1 0 2H21a1 1 0 0 0-1 1v3.5a1 1 0 1 1-2 0z");
}

</style>
