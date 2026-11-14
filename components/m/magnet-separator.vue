<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f3fu1c41a"/><path class="lv1iz44xa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magnet-separator" /></template>
<style>
.f3fu1c41a {
  d: path("M4 15v-5a8 8 0 0 1 16 0v5h-4v-5a4 4 0 0 0-8 0v5Zm0-3h4m8 0h4");
}

.lv1iz44xa {
  fill: currentColor;
  d: path("m5.167 18.133l2.35.855l-.684 1.879l-2.35-.855ZM10.75 21L12 18.5l1.25 2.5Zm5.784-1.892l2.415-.647l.517 1.931l-2.415.647Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
