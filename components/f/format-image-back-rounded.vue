<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft3td-btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-image-back-rounded" /></template>
<style>
.ft3td-btl {
  fill: currentColor;
  d: path("M19.5 20h-15q-.213 0-.356-.144T4 19.499t.144-.356T4.5 19h15q.213 0 .356.144t.144.357t-.144.356T19.5 20m0-3.75h-15q-.213 0-.356-.144T4 15.749t.144-.356t.356-.143h3.25V12.5H4.5q-.213 0-.356-.144T4 11.999t.144-.356t.356-.143h3.25V8.75H4.5q-.213 0-.356-.144T4 8.249t.144-.356t.356-.143h15q.213 0 .356.144t.144.357t-.144.356t-.356.143h-3.25v2.75h3.25q.213 0 .356.144t.144.357t-.144.356t-.356.143h-3.25v2.75h3.25q.213 0 .356.144t.144.357t-.144.356t-.356.143M19.5 5h-15q-.213 0-.356-.144T4 4.499t.144-.356T4.5 4h15q.213 0 .356.144t.144.357t-.144.356T19.5 5");
}

</style>
