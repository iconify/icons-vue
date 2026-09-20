<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eqgw32bhd"/><path class="sgsfq910e"/><path class="xku-v5b9r"/><path class="zv4xbjb0b"/><path class="l378wbglq"/><path class="mf83r869e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-flutter-opened" /></template>
<style>
.eqgw32bhd {
  fill: var(--svg-color--786fe7, #786fe7);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.l378wbglq {
  fill: var(--svg-color--095a9d, #095a9d);
  d: path("M24.747 24.641L30.045 30h-6.1l-2.295-2.28z");
}

.mf83r869e {
  fill: var(--svg-color--0e5199, #0e5199);
  d: path("M23.563 25.818L21.65 27.72l2.885-.96z");
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
