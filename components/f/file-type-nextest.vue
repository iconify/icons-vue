<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="iqqd6-b1t"/><path class="y365p6ady"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-nextest" /></template>
<style>
.iqqd6-b1t {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 2px;
  fill: var(--svg-color--045, #045);
  rx: 5.25px;
}

.y365p6ady {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.45 10.13h5.03v5.03H8.45zm1.68 1.68v1.67h1.68v-1.67zm5.03 0h8.39v1.67h-8.39zm0 6.7h8.39v1.68h-8.39zm-5.03 4.2L7.2 19.77l1.18-1.18l1.75 1.75l3.85-3.85l1.18 1.19z");
}

</style>
