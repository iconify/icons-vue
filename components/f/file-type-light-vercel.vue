<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGmAm0PeNo" x1="1.288" x2="1.143" y1="32.55" y2="32.75" gradientTransform="matrix(114 0 0 -100 -113 3301)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1"/></linearGradient></defs><path fill="url(#SVGmAm0PeNo)" class="wf7l8vb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-vercel" /></template>
<style>
.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wf7l8vb4x {
  fill-rule: evenodd;
  d: path("m16 3.719l14 24.562H2z");
}

</style>
