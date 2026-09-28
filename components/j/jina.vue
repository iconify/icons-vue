<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":218};
const content = `<circle class="ble_nj8nm"/><path class="rahgtwbji"/><circle class="ibmpf9bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:jina" /></template>
<style>
.ble_nj8nm {
  cx: 33.377px;
  cy: 184.337px;
  r: 33.377px;
  fill: var(--svg-color--eb6161, #eb6161);
}

.ibmpf9bqt {
  cx: 215.422px;
  cy: 33.377px;
  r: 33.377px;
  fill: var(--svg-color--fbcb67, #fbcb67);
}

.rahgtwbji {
  fill: var(--svg-color--009191, #009191);
  d: path("M138.526 79.189a7.82 7.82 0 0 1 7.853 7.853l-.436 63.918c0 36.432-29.232 66.1-65.663 66.755h-1.091V87.26c0-4.363 3.926-8.071 8.29-8.071zm102.53 0a7.82 7.82 0 0 1 7.854 7.853v89.442a7.82 7.82 0 0 1-7.853 7.853h-51.048a7.82 7.82 0 0 1-7.853-7.853V87.042a7.82 7.82 0 0 1 7.853-7.853zm80.28-.218h1.09c32.724.436 59.338 26.832 60.21 59.555v37.74a7.82 7.82 0 0 1-7.853 7.853h-82.46a7.82 7.82 0 0 1-7.854-7.853V86.824a7.82 7.82 0 0 1 7.853-7.853zm135.036 104.276c-27.487-1.746-49.52-24.651-49.52-52.575c0-29.014 23.56-52.574 52.574-52.574c27.923 0 50.829 21.815 52.574 49.52v47.775a7.82 7.82 0 0 1-7.853 7.854z");
}

</style>
