<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="nawiv8r4k"/><path class="bvifnyb9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-flue" /></template>
<style>
.bvifnyb9n {
  fill: var(--svg-color--fff, #fff);
  d: path("M16 6.667h4.666v4.666H16zm-4.667 14H16v4.666h-4.667zm0-9.334H16V16h-4.667zM16 16h4.666v4.667H16z");
}

.ft5dv1b6b {
  fill: none;
}

.nawiv8r4k {
  fill: var(--svg-color--007aff, #007aff);
  d: path("M2 2h28v28H2z");
}

</style>
