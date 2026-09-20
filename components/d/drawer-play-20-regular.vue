<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kzuk0zx4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:drawer-play-20-regular" /></template>
<style>
.kzuk0zx4r {
  fill: currentColor;
  d: path("M17 9.743V15a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h2.207a5.5 5.5 0 0 0-.185 1H6a2 2 0 0 0-2 2h4.207q.149.524.393 1H4v3h3.5a.5.5 0 0 1 .5.5a2 2 0 1 0 4 0a.5.5 0 0 1 .5-.5H16v-.6a5.5 5.5 0 0 0 1-.657M14 17a2 2 0 0 0 2-2v-3h-3.041a3 3 0 0 1-5.918 0H4v3a2 2 0 0 0 2 2zm-.5-7a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m-.757-6.587l2.97 1.65a.5.5 0 0 1 0 .874l-2.97 1.65A.5.5 0 0 1 12 7.15v-3.3a.5.5 0 0 1 .743-.437");
}

</style>
