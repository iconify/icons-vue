<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":259};
const content = `<g class="c7phqccsc"><circle class="tshen9bpf"/><path class="zvumuob-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:circleci" /></template>
<style>
.c7phqccsc {
  fill: var(--svg-color--343434, #343434);
}

.tshen9bpf {
  cx: 126.157px;
  cy: 129.008px;
  r: 30.593px;
}

.zvumuob-r {
  d: path("M1.204 96.572c0 .368-.369 1.105-.369 1.474c0 3.317 2.58 6.266 6.266 6.266h51.972c2.58 0 4.423-1.474 5.529-3.686c10.69-23.59 34.28-39.44 61.186-39.44c37.228 0 67.453 30.225 67.453 67.453s-30.225 67.453-67.453 67.453c-27.276 0-50.497-16.218-61.186-39.071c-1.106-2.58-2.949-4.055-5.53-4.055H7.103c-3.318 0-6.267 2.58-6.267 6.267c0 .368 0 1.105.369 1.474c14.375 56.026 64.872 97.309 124.953 97.309c71.139 0 129.008-57.87 129.008-129.008S197.295 0 126.157 0C66.077 0 15.579 41.283 1.204 96.572");
}

</style>
