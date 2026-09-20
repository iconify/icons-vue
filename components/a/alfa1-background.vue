<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hmxee7bms"/><path clip-rule="evenodd" class="wa58jebxk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:alfa1-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hmxee7bms {
  fill: var(--svg-color--0156fe, #0156fe);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wa58jebxk {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.357 11.184c.397 0 .744.134 1.012.354l-.008-.254h1.04v3.434h-1.04l.008-.24c-.251.196-.588.322-1.012.322c-.9 0-1.747-.684-1.747-1.808c0-1.1.808-1.808 1.747-1.808M20 9.794v4.928h-1.086V10.75h-1.02l.41-.955zM7.654 9.238v5.485H6.629v-1.015h-1.1l-.4 1.015H4l2.233-5.485zM9.56 9.2v5.522H8.537V9.2zm2.282.038c.23 0 .53.042.573.049v.832a2 2 0 0 0-.294-.022c-.157 0-.25.029-.308.07c-.147.118-.15.667-.15 1.02h.709v.74h-.716v2.795h-1.003v-2.794h-.422v-.74h.422v-.035c0-.226-.007-.513.007-.724c.029-.402.072-1.198 1.182-1.191m2.672 2.84a.914.914 0 0 0 0 1.828a.914.914 0 0 0 0-1.828M6.63 10.743L5.9 12.77h.73z");
}

</style>
