<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj7r5abjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dangerous" /></template>
<style>
.oj7r5abjl {
  fill: currentColor;
  d: path("M8.673 20L4 15.327V8.673L8.673 4h6.654L20 8.673v6.654L15.327 20zm.477-4.442l2.85-2.85l2.85 2.85l.708-.708l-2.85-2.85l2.85-2.85l-.708-.708l-2.85 2.85l-2.85-2.85l-.708.708l2.85 2.85l-2.85 2.85z");
}

</style>
