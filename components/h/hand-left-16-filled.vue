<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dckw51bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hand-left-16-filled" /></template>
<style>
.dckw51bpl {
  fill: currentColor;
  d: path("M7.5 1.75a.75.75 0 0 1 1.5 0V6.5a.5.5 0 0 0 1 0V2.75a.75.75 0 0 1 1.5 0V7.5a.5.5 0 1 0 1 0V4.75a.75.75 0 0 1 1.5-.002V9.5c0 .813-.344 1.71-.743 2.492a16 16 0 0 1-1.283 2.059c-.45.622-1.171.949-1.91.949H7.736c-.952 0-1.797-.54-2.255-1.34a36 36 0 0 0-2.233-3.38a41 41 0 0 0-1.112-1.435l-.016-.02l-.003-.004h-.001a.5.5 0 0 1 .03-.675c.351-.35.766-.493 1.187-.482c.4.01.778.159 1.096.336c.202.111.394.243.57.379V2.75a.75.75 0 0 1 1.5 0V6.5a.5.5 0 0 0 1.001 0z");
}

</style>
