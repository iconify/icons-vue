<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="dj9-_2dwo"/><path class="p2kkocbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-xposed" /></template>
<style>
.dj9-_2dwo {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 2px;
  fill: var(--svg-color--f48fb1, #f48fb1);
  rx: 5px;
}

.p2kkocbqq {
  fill: var(--svg-color--fff, #fff);
  d: path("m20.457 16.016l3.095-3.096a.775.775 0 0 0 0-1.097l-3.375-3.375a.775.775 0 0 0-1.097 0l-3.096 3.095l-3.095-3.095a.78.78 0 0 0-1.097 0l-3.375 3.375a.775.775 0 0 0 0 1.097l3.095 3.096l-3.095 3.095a.775.775 0 0 0 0 1.097l3.375 3.375a.775.775 0 0 0 1.097 0l3.095-3.095l3.096 3.095c.156.156.35.226.552.226a.8.8 0 0 0 .552-.226l3.376-3.375a.775.775 0 0 0 0-1.097zM16 13.666c.428 0 .778.35.778.778s-.35.778-.778.778s-.778-.35-.778-.778s.35-.777.778-.777m-3.663 1.525l-2.824-2.815l2.824-2.824l2.815 2.816zm2.107 1.587c-.427 0-.777-.35-.777-.778s.35-.778.777-.778s.778.35.778.778s-.35.778-.778.778M16 18.333c-.428 0-.778-.35-.778-.777s.35-.778.778-.778s.778.35.778.778s-.35.777-.778.777m1.556-3.11c.427 0 .777.35.777.777s-.35.778-.777.778s-.778-.35-.778-.778s.35-.778.778-.778m2.068 7.264l-2.823-2.816l2.823-2.823l2.816 2.815z");
}

</style>
