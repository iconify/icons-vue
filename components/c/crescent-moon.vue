<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nlstqybtq"/><g class="eyuj09bzi"><path class="mvh0u2bpk"/><circle class="bozfwmbpy"/><circle class="pkk7cir0l"/><path class="m9hu5ifxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:crescent-moon" /></template>
<style>
.bozfwmbpy {
  cx: 32.27px;
  cy: 57.38px;
  r: 3.486px;
}

.eyuj09bzi {
  fill: var(--svg-color--e0cf35, #e0cf35);
}

.m9hu5ifxs {
  d: path("M47.667 12.575a2.07 2.07 0 1 0 4.14.001a2.07 2.07 0 0 0-4.14-.001");
}

.mvh0u2bpk {
  d: path("M56.745 40.26a2.544 2.544 0 0 0 2.548 2.545a2.548 2.548 0 1 0-2.548-2.545");
}

.nlstqybtq {
  fill: var(--svg-color--f5eb35, #f5eb35);
  d: path("M44.1 31.02c1-17.417-7.735-26.423-10.353-30.549c14.396 3.137 30.09 10.526 30.09 31.28c0 17.689-14.339 32.03-32.03 32.03a31.8 31.8 0 0 1-16.11-4.381c8.664-4.876 27.4-10.957 28.4-28.373");
}

.pkk7cir0l {
  cx: 47.895px;
  cy: 45.18px;
  r: 5.861px;
}

</style>
