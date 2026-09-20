<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bptlog-4c"/><path class="z77u1f8zt"/><ellipse class="l-fuhbc4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-systemd" /></template>
<style>
.bptlog-4c {
  fill: var(--svg-color--201a26, #201a26);
  d: path("M2 12v8h3.256v-1.231H3.3v-5.538h1.956V12Zm24.744 0v1.231H28.7v5.538h-1.956V20H30v-8Z");
}

.l-fuhbc4k {
  cx: 12.093px;
  cy: 16px;
  fill: var(--svg-color--30d475, #30d475);
  rx: 2.93px;
  ry: 2.769px;
}

.z77u1f8zt {
  fill: var(--svg-color--30d475, #30d475);
  d: path("m17.628 16l5.21-2.769v5.538Z");
}

</style>
