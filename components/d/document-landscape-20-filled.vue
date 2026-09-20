<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fyd94nb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-landscape-20-filled" /></template>
<style>
.fyd94nb3k {
  fill: currentColor;
  d: path("M18 10h-4.5A1.5 1.5 0 0 1 12 8.5V4H3.5A1.5 1.5 0 0 0 2 5.5v9A1.5 1.5 0 0 0 3.5 16h13a1.5 1.5 0 0 0 1.5-1.5zm-.25-1H13.5a.5.5 0 0 1-.5-.5V4.25z");
}

</style>
