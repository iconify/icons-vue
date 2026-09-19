<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="m5qjw3o7z"/><circle class="kyrv5hb3t"/><path class="ux5q7_bcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:frowning-face" /></template>
<style>
.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.kyrv5hb3t {
  cx: 43.5px;
  cy: 24.6px;
  r: 5px;
}

.m5qjw3o7z {
  cx: 20.5px;
  cy: 24.6px;
  r: 5px;
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.ux5q7_bcf {
  d: path("M19.4 45.8c8.1-5.7 17.1-5.6 25.2 0c1 .7 1.8-.5 1.2-1.6c-2.5-4-7.4-7.7-13.8-7.7s-11.3 3.6-13.8 7.7c-.6 1.1.2 2.3 1.2 1.6");
}

</style>
