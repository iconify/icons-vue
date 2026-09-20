<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rkmo6-rwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-multiple-32-regular" /></template>
<style>
.rkmo6-rwc {
  fill: currentColor;
  d: path("M27.99 10.253A4.5 4.5 0 0 1 30 14v6a8 8 0 0 1-8 8H10a4.5 4.5 0 0 1-3.745-2.007q.12.006.243.007H22a6 6 0 0 0 6-6v-6l-.002-.04V10.5q0-.124-.007-.247M9.965 3a3.5 3.5 0 0 1 2.475 1.025L14.414 6H22a4.5 4.5 0 0 1 4.5 4.5V20a4.5 4.5 0 0 1-4.5 4.5H6.5A4.5 4.5 0 0 1 2 20V7.5A4.5 4.5 0 0 1 6.5 3zm2.475 6.975A3.5 3.5 0 0 1 9.965 11H4v9a2.5 2.5 0 0 0 2.5 2.5H22a2.5 2.5 0 0 0 2.5-2.5v-9.5A2.5 2.5 0 0 0 22 8h-7.586zM6.5 5A2.5 2.5 0 0 0 4 7.5V9h5.965a1.5 1.5 0 0 0 1.06-.44L12.585 7l-1.56-1.56A1.5 1.5 0 0 0 9.965 5z");
}

</style>
