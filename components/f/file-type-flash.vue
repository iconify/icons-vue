<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGZ4iYYdzD" x1="28.841" x2="3.828" y1="29.545" y2="3.161" gradientUnits="userSpaceOnUse"><stop offset="0" class="x8wq6bb8j"/><stop offset="1" class="o_xriccpi"/></linearGradient></defs><path fill="url(#SVGZ4iYYdzD)" class="vuck01vqy"/><path class="aybj7wz6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-flash" /></template>
<style>
.aybj7wz6o {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M21.56 10.892a4.7 4.7 0 0 1 1.546-.243V7.122a7.44 7.44 0 0 0-6.115 2.884a11.4 11.4 0 0 0-1.529 2.571l-1.147 2.8a23 23 0 0 1-1.025 2.519a10 10 0 0 1-1.06 1.876a4 4 0 0 1-1.39 1.147a4.5 4.5 0 0 1-1.946.4v3.561a7.49 7.49 0 0 0 6.115-2.884a13.4 13.4 0 0 0 1.251-2.015l.973-2.224h4.082v-3.546h-2.692a11 11 0 0 1 .8-1.529a4.6 4.6 0 0 1 .938-1.095a3.6 3.6 0 0 1 1.2-.695Z");
}

.o_xriccpi {
  stop-color: var(--svg-color--d42027, #d42027);
}

.vuck01vqy {
  d: path("M2 2.328h28v27.344H2z");
}

.x8wq6bb8j {
  stop-color: var(--svg-color--b42025, #b42025);
}

</style>
