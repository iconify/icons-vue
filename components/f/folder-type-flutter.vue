<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ecbenyb2y"/><path class="sgsfq910e"/><path class="xku-v5b9r"/><path class="zv4xbjb0b"/><path class="l378wbglq"/><path class="h0-s51bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-flutter" /></template>
<style>
.ecbenyb2y {
  fill: var(--svg-color--584be2, #584be2);
  d: path("M27.417 5.5H18.19l-2.083 4.2H4.5v16.8h25v-21Zm0 4.2h-8.135l1.091-2.1h7.044Z");
}

.h0-s51bln {
  fill: var(--svg-color--0e5199, #0e5199);
  d: path("m21.65 27.72l2.885-.96l-.972-.942z");
}

.l378wbglq {
  fill: var(--svg-color--095a9d, #095a9d);
  d: path("M24.747 24.641L30.045 30h-6.1l-2.295-2.28z");
}

.sgsfq910e {
  fill: var(--svg-color--40d0fd, #40d0fd);
  d: path("m21.612 21.646l2.442-2.379h6.067l-5.374 5.374z");
}

.xku-v5b9r {
  fill: var(--svg-color--41d0fd, #41d0fd);
  d: path("M17.051 23.178L30.121 10h-6.067L14 20.054z");
}

.zv4xbjb0b {
  fill: var(--svg-color--1fbcfd, #1fbcfd);
  d: path("m21.65 27.72l3.097-3.079l-3.135-2.995l-3.057 3.025z");
}

</style>
