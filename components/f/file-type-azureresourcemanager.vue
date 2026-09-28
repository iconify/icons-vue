<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y1in4gbts"/><path class="r8qepp96z"/><path class="ef6m9usoz"/><path class="x4-5pmjnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-azureresourcemanager" /></template>
<style>
.ef6m9usoz {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.17 26.24l-.13-.03a.3.3 0 0 1-.12-.22v-9.45q0-.14.12-.22l8.2-4.74a.3.3 0 0 1 .26 0q.11.08.12.22v9.45q0 .15-.12.22l-8.21 4.74z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.r8qepp96z {
  fill: var(--svg-color--59b4d9, #59b4d9);
  d: path("m14.84 26.24l-.12-.03l-8.22-4.74a.2.2 0 0 1-.12-.22v-9.51q0-.15.12-.22a.3.3 0 0 1 .25 0l8.22 4.74q.11.08.12.22v9.51q0 .15-.12.22zm2.33 0l-.13-.03a.3.3 0 0 1-.12-.22v-9.45q0-.14.12-.22l8.2-4.74a.3.3 0 0 1 .26 0q.11.08.12.22v9.45q0 .15-.12.22l-8.21 4.74z");
}

.x4-5pmjnn {
  fill: var(--svg-color--7a7a7a, #7a7a7a);
  d: path("M7.35 27.3a1 1 0 0 1-.4-.11L3.1 24.97A2.4 2.4 0 0 1 2 23.05V8.95c0-.74.47-1.55 1.11-1.92L6.95 4.8a.81.81 0 0 1 .81 1.41L3.93 8.44a.8.8 0 0 0-.3.51v14.1c0 .15.16.43.3.51l3.83 2.22a.81.81 0 0 1-.4 1.52M24.65 4.7q.22 0 .4.11l3.84 2.22A2.4 2.4 0 0 1 30 8.95v14.1c0 .74-.47 1.55-1.11 1.92l-3.84 2.22a.81.81 0 0 1-.81-1.41l3.83-2.22c.14-.08.3-.36.3-.51V8.95a.8.8 0 0 0-.3-.51l-3.83-2.22a.81.81 0 0 1 .4-1.52");
}

.y1in4gbts {
  fill: var(--svg-color--3999c6, #3999c6);
  d: path("m16.03 14.68l-.13-.03l-8.24-4.76a.25.25 0 0 1 0-.43l8.19-4.72a.3.3 0 0 1 .25 0l8.24 4.75q.11.08.12.22t-.12.21l-8.19 4.73z");
}

</style>
