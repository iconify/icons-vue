<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q3wixnhae"/><path class="hx46wmbfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:folder-cog" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hx46wmbfi {
  d: path("m11.5 10.608l.007-.112a.494.494 0 0 1 .493-.465a.494.494 0 0 1 .493.465l.007.112a.72.72 0 0 0 .441.62a.72.72 0 0 0 .751-.127l.083-.074a.494.494 0 0 1 .678.02a.494.494 0 0 1 .02.678l-.074.083a.72.72 0 0 0-.127.751a.72.72 0 0 0 .62.441l.112.007a.494.494 0 0 1 .465.493a.494.494 0 0 1-.465.493l-.112.007a.72.72 0 0 0-.62.441a.72.72 0 0 0 .127.751l.074.083a.494.494 0 0 1-.02.678a.494.494 0 0 1-.678.02l-.083-.074a.72.72 0 0 0-.751-.127a.72.72 0 0 0-.441.62l-.007.112a.494.494 0 0 1-.493.465a.494.494 0 0 1-.493-.465l-.007-.112a.72.72 0 0 0-.441-.62a.72.72 0 0 0-.751.127l-.083.074a.494.494 0 0 1-.678-.02a.494.494 0 0 1-.02-.678l.074-.083a.72.72 0 0 0 .127-.751a.72.72 0 0 0-.62-.441l-.112-.007a.494.494 0 0 1-.465-.493a.494.494 0 0 1 .465-.493L9.108 13a.72.72 0 0 0 .62-.441a.72.72 0 0 0-.127-.751l-.074-.083a.494.494 0 0 1 .02-.678a.494.494 0 0 1 .678-.02l.083.074a.72.72 0 0 0 .751.127a.72.72 0 0 0 .441-.62");
}

.q3wixnhae {
  d: path("M3 7a2 2 0 0 1 2-2h4.5l2 2H19a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

</style>
