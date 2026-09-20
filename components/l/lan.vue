<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp9u1ybns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lan" /></template>
<style>
.cp9u1ybns {
  fill: currentColor;
  d: path("M3 22v-7h3v-4h5V9H8V2h8v7h-3v2h5v4h3v7h-8v-7h3v-2H8v2h3v7z");
}

</style>
