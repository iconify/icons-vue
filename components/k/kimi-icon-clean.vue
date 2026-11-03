<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="peckbobtj"/><path class="qhejlxbvj"/><path class="t0zm1fr4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:kimi-icon-clean" /></template>
<style>
.peckbobtj {
  d: path("M256 64v128c0 35.322-28.678 64-64 64H64c-35.322 0-64-28.678-64-64V64C0 28.678 28.678 0 64 0h128c35.322 0 64 28.678 64 64");
}

.qhejlxbvj {
  fill: var(--svg-color--1783ff, #1783ff);
  d: path("M202.854 45.53c7.264 0 13.152 5.888 13.152 13.152s-5.888 13.152-13.152 13.152h-11.603a1.546 1.546 0 0 1-1.549-1.55V58.683c0-7.264 5.888-13.152 13.152-13.152");
}

.t0zm1fr4k {
  fill: var(--svg-color--fff, #fff);
  d: path("m129.126 122.112l49.626-49.242c.934-.928.41-2.79-.794-2.79h-26.707c-.288 0-.57.115-.8.346L96.98 123.462c-.832.82-2.067.09-2.067-1.222V71.648c0-.87-.57-1.568-1.267-1.568h-18.4c-.698 0-1.267.698-1.267 1.568V180.73c0 .87.57 1.568 1.267 1.568h18.4c.697 0 1.267-.698 1.267-1.568v-22.228c0-.473.173-.928.474-1.222l16.576-16.448c.403-.397.953-.454 1.401-.16l44.34 32.634c7.263 4.883 15.379 7.884 23.615 8.774c.736.077 1.37-.653 1.37-1.568v-20.934c0-.8-.48-1.453-1.126-1.55c-4.852-.76-9.581-2.636-13.856-5.516l-38.394-27.795c-.794-.531-.896-1.907-.186-2.605");
}

</style>
