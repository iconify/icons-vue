<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a6uzp-w8l"/><path class="c7dnfwbxg"/><path class="e02zkkq1y"/><path class="e6zp4b9zo"/><path class="p0-as-b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-temp-opened" /></template>
<style>
.a6uzp-w8l {
  fill: var(--svg-color--2e8e80, #2e8e80);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.c7dnfwbxg {
  fill: var(--svg-color--2e8e80, #2e8e80);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.e02zkkq1y {
  fill: var(--svg-color--5fc1b3, #5fc1b3);
  d: path("M21 31a10 10 0 1 1 10-10a10.01 10.01 0 0 1-10 10m0-18.182A8.182 8.182 0 1 0 29.182 21A8.19 8.19 0 0 0 21 12.818");
}

.e6zp4b9zo {
  fill: var(--svg-color--5fc1b3, #5fc1b3);
  d: path("M21.909 21.909h-1.068a.75.75 0 0 1-.75-.75v-6.682a.75.75 0 0 1 .75-.75h.318a.75.75 0 0 1 .75.75Z");
}

.p0-as-b5u {
  fill: var(--svg-color--5fc1b3, #5fc1b3);
  d: path("M27.523 21.909h-6.682a.75.75 0 0 1-.75-.75v-1.068h7.432a.75.75 0 0 1 .75.75v.318a.75.75 0 0 1-.75.75");
}

</style>
