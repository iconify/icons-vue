<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qllct5s3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drag-handle-outline-rounded" /></template>
<style>
.qllct5s3t {
  fill: currentColor;
  d: path("M5.5 14.5q-.213 0-.356-.144T5 13.999t.144-.356t.356-.143h13q.213 0 .356.144t.144.357t-.144.356t-.356.143zm0-4q-.213 0-.356-.144T5 9.999t.144-.356T5.5 9.5h13q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
