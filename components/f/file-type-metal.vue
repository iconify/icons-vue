<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGVmRvNeOe)" class="axwn6acrs"/><path class="wumx3hbcz"/><defs><linearGradient id="SVGVmRvNeOe" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="tpf0odbjk"/><stop offset="1" class="jr6j1k5pd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-metal" /></template>
<style>
.axwn6acrs {
  d: path("M24.4 30H7.6A5.6 5.6 0 0 1 2 24.4V7.6C2 4.508 4.508 2 7.6 2h16.8C27.492 2 30 4.508 30 7.6v16.8c0 3.092-2.508 5.6-5.6 5.6");
}

.ft5dv1b6b {
  fill: none;
}

.jr6j1k5pd {
  stop-color: var(--svg-color--4e0ac9, #4e0ac9);
}

.tpf0odbjk {
  stop-color: var(--svg-color--e94151, #e94151);
}

.wumx3hbcz {
  fill: var(--svg-color--000, #000);
  d: path("M7.483 23.194V7.134l7.506 9.177V9.583l12.328 13.611h-3.19l-6.65-7.038l-.077 7.038l-7.428-9.177v9.177z");
}

</style>
