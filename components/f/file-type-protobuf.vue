<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yptk-kbkc"/><path class="nhg5ylbmd"/><path class="dxmzmcc8d"/><path class="c7qkbdcdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-protobuf" /></template>
<style>
.c7qkbdcdj {
  fill: var(--svg-color--0f9855, #0f9855);
  d: path("M17.656 8.456h6.402c5.358 7 5.59 7.26 5.594 7.58c.003.322-.047.469-3.018 4.27z");
}

.dxmzmcc8d {
  fill: var(--svg-color--4081ec, #4081ec);
  d: path("M2.348 16.037c0-.399.007-.402 2.87-4.269l9.052 11.775H7.794c-5.443-7.047-5.446-7.056-5.446-7.506");
}

.nhg5ylbmd {
  fill: var(--svg-color--f7bb07, #f7bb07);
  d: path("M23.175 15.816h3.46v4.49l-2.503 3.237h-6.476z");
}

.yptk-kbkc {
  fill: var(--svg-color--d44235, #d44235);
  d: path("m5.218 11.768l2.429-3.312h6.623l-5.74 7.728H5.218z");
}

</style>
