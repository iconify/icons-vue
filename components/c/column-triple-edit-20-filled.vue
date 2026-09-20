<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qybfohlae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:column-triple-edit-20-filled" /></template>
<style>
.qybfohlae {
  fill: currentColor;
  d: path("M1 15a2 2 0 0 0 2 2h1a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2H3a2 2 0 0 0-2 2zm6 0a2 2 0 0 0 2 2h.22l.212-.845a3.2 3.2 0 0 1 .84-1.485L12 12.943V5a2 2 0 0 0-2-2H9a2 2 0 0 0-2 2zm11-5.866a2.87 2.87 0 0 0-2.898.707L13 11.943V5a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2zm-7.02 6.243l4.83-4.83a1.87 1.87 0 1 1 2.644 2.646l-4.83 4.829a2.2 2.2 0 0 1-1.02.578l-1.498.374a.89.89 0 0 1-1.079-1.078l.375-1.498a2.2 2.2 0 0 1 .578-1.02");
}

</style>
