<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cb7__hbyb"/><path class="e02zkkq1y"/><path class="e6zp4b9zo"/><path class="p0-as-b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-temp" /></template>
<style>
.cb7__hbyb {
  fill: var(--svg-color--34756b, #34756b);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
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
