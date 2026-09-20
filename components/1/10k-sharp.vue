<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1c6bpbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:10k-sharp" /></template>
<style>
.m1c6bpbxo {
  fill: currentColor;
  d: path("M6.77 14.692h.884V9.308h-2.27v.884H6.77zm2.346 0H13V9.308H9.116zm.884-.884v-3.616h2.116v3.616zm4.462.884h.884v-2.365l2.289 2.365h1.211l-2.634-2.73l2.634-2.654h-1.173l-2.327 2.327V9.308h-.884zM4 20V4h16v16z");
}

</style>
