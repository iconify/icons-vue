<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u2fbhpbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-multiple-32-filled" /></template>
<style>
.u2fbhpbxn {
  fill: currentColor;
  d: path("M27.99 10.253A4.5 4.5 0 0 1 30 14v6a8 8 0 0 1-8 8H10a4.5 4.5 0 0 1-3.745-2.007q.12.006.243.007H22a6 6 0 0 0 6-6v-6l-.002-.04V10.5q0-.124-.007-.247M22 6a4.5 4.5 0 0 1 4.5 4.5V20a4.5 4.5 0 0 1-4.5 4.5H6.5A4.5 4.5 0 0 1 2 20v-9h7.965a3.5 3.5 0 0 0 2.475-1.025l3.767-3.768A1 1 0 0 0 16.364 6zM9.965 3a3.5 3.5 0 0 1 2.475 1.025L14 5.585l-2.975 2.976A1.5 1.5 0 0 1 9.965 9H2V7.5A4.5 4.5 0 0 1 6.5 3z");
}

</style>
