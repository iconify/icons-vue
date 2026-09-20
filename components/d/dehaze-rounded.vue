<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_tyfpbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dehaze-rounded" /></template>
<style>
.d_tyfpbzy {
  fill: currentColor;
  d: path("M4.5 7q-.213 0-.356-.144T4 6.499t.144-.356T4.5 6h15q.213 0 .356.144t.144.357t-.144.356T19.5 7zm0 11q-.213 0-.356-.144T4 17.499t.144-.356T4.5 17h15q.213 0 .356.144t.144.357t-.144.356T19.5 18zm0-5.5q-.213 0-.356-.144T4 11.999t.144-.356t.356-.143h15q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
