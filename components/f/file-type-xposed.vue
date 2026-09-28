<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="dj9-_2dwo"/><path class="ya9ao4bvi"/>`;
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

.ya9ao4bvi {
  fill: var(--svg-color--fff, #fff);
  d: path("m20.457 16.016l3.096-3.096a.775.775 0 0 0 0-1.096l-3.376-3.376a.775.775 0 0 0-1.097 0l-3.095 3.096l-3.096-3.096a.78.78 0 0 0-1.097 0l-3.375 3.376a.775.775 0 0 0 0 1.096l3.096 3.096l-3.096 3.095a.775.775 0 0 0 0 1.097l3.376 3.376a.775.775 0 0 0 1.096 0l3.096-3.096l3.095 3.096c.156.155.35.225.553.225a.8.8 0 0 0 .552-.225l3.375-3.376a.775.775 0 0 0 0-1.097zM16 13.667c.428 0 .778.35.778.778s-.35.778-.778.778s-.777-.35-.777-.778s.35-.778.777-.778m-3.663 1.524l-2.823-2.815l2.823-2.823l2.816 2.815zm2.108 1.587c-.428 0-.778-.35-.778-.778s.35-.777.778-.777s.778.35.778.777s-.35.778-.778.778M16 18.334c-.427 0-.777-.35-.777-.778s.35-.778.777-.778s.778.35.778.778s-.35.778-.778.778m1.556-3.111c.428 0 .778.35.778.777s-.35.778-.778.778s-.778-.35-.778-.778s.35-.777.778-.777m2.069 7.264L16.8 19.671l2.824-2.823l2.815 2.816z");
}

</style>
