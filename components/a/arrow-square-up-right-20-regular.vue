<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u_62u7bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-square-up-right-20-regular" /></template>
<style>
.u_62u7bvp {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zM4 6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2zm8.691 1.038q.088.036.16.106l.005.005A.5.5 0 0 1 13 7.5v5a.5.5 0 0 1-1 0V8.707l-4.146 4.147a.5.5 0 0 1-.708-.708L11.293 8H7.5a.5.5 0 0 1 0-1h5q.102 0 .191.038");
}

</style>
