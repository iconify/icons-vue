<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ijkf34b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-square-28-regular" /></template>
<style>
.ijkf34b_w {
  fill: currentColor;
  d: path("M21.25 3A3.75 3.75 0 0 1 25 6.75v14.5A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3zM6.75 4.5A2.25 2.25 0 0 0 4.5 6.75v14.5a2.25 2.25 0 0 0 2.25 2.25h14.5a2.25 2.25 0 0 0 2.25-2.25V6.75a2.25 2.25 0 0 0-2.25-2.25zm10.97 4.72a.75.75 0 1 1 1.06 1.06L15.06 14l3.72 3.72a.75.75 0 1 1-1.06 1.06L14 15.06l-3.72 3.72a.75.75 0 1 1-1.06-1.06L12.94 14l-3.72-3.72a.75.75 0 1 1 1.06-1.06L14 12.94z");
}

</style>
