<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nvbxvqb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-16-filled" /></template>
<style>
.nvbxvqb9m {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m0 2a5 5 0 0 0-3.144 8.889a.5.5 0 0 0 .63-.778a4 4 0 0 1 2.959-7.087a.5.5 0 0 0 .11-.994A5 5 0 0 0 8 3m4.418 4.003a.5.5 0 0 0-.442.552Q12 7.774 12 8c0 1.256-.58 2.377-1.486 3.111a.5.5 0 0 0 .63.778a4.99 4.99 0 0 0 1.826-4.444a.5.5 0 0 0-.552-.442m-1.286-2.486c-.337-.09-.63.224-.921.416c-.86.566-2.722 1.809-3.095 2.181a1.25 1.25 0 0 0 1.768 1.768c.373-.373 1.62-2.237 2.186-3.095c.191-.288.502-.578.415-.913a.5.5 0 0 0-.353-.357");
}

</style>
