<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zg-y7zrnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-video-20-filled" /></template>
<style>
.zg-y7zrnd {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5V5H2zM2 6h12v2H8.5A3.5 3.5 0 0 0 5 11.5V14h-.5A2.5 2.5 0 0 1 2 11.5zm4 5.5A2.5 2.5 0 0 1 8.5 9h5a2.5 2.5 0 0 1 2.5 2.5v.129l2.035-1.405a1.25 1.25 0 0 1 1.96 1.028v5.498a1.25 1.25 0 0 1-1.96 1.028L16 16.373v.127a2.5 2.5 0 0 1-2.5 2.5h-5A2.5 2.5 0 0 1 6 16.5z");
}

</style>
