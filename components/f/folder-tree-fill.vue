<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="lgy072b_c"/><path class="zds66r9hy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-tree-fill" /></template>
<style>
.lgy072b_c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 2L15.382 2C16.1395 2 16.832 2.428 17.1708 3.1056L17.618 4L20 4C21.1046 4 22 4.8954 22 6L22 9C22 10.1046 21.1046 11 20 11L14 11C12.8954 11 12 10.1046 12 9L12 4C12 2.8954 12.8954 2 14 2ZM14 13L15.382 13C16.1395 13 16.832 13.428 17.1708 14.1056L17.618 15L20 15C21.1046 15 22 15.8954 22 17L22 20C22 21.1046 21.1046 22 20 22L14 22C12.8954 22 12 21.1046 12 20L12 15C12 13.8954 12.8954 13 14 13Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zds66r9hy {
  d: path("M3 3L3 16C3 17.6569 4.3431 19 6 19L9 19M3 5C3 6.6569 4.3431 8 6 8L9 8");
}

</style>
