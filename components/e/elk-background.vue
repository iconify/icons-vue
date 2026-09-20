<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="n2d5d5bri"/><path class="mvdes_b4s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:elk-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mvdes_b4s {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 14.6v-1.564L7.12 8.192a2.3 2.3 0 0 0-.452-.392c-.228 0-.48.084-.62.196c-.144.112-.34.728-.536 1.008c-.2.28-1.24.504-1.384.616c-.14.112-.128 1.14-.128 1.504c0 .276.608.276.72.276s.256-.22.256-.304c.92-.584 1.572-.504 1.824-.496l1.2 1c-.256.12-.888.44-1 .484c-.144.056-.2.308-.2.952s.168.764.396.764c.224 0 .308-.084.364-.14c.252-.248 1.4-.52 1.872-.66c.228.224.52.712.568.8c-.48.084-1.216.496-1.36.58c-.14.084-.24 1.24-.24 1.52c0 .228.536.3.8.3c.04-.04.12-.136.12-.224c.52-.4 1.716-.712 2.28-.776zm0 0v-1.564l4.88-4.844c.144-.14.4-.392.452-.392c.228 0 .48.084.62.196c.144.112.34.728.536 1.008c.2.28 1.24.504 1.384.616c.14.112.128 1.14.128 1.504c0 .276-.608.276-.72.276s-.256-.22-.256-.304c-.92-.584-1.572-.504-1.824-.496l-1.2 1c.252.12.888.44 1 .484c.144.056.2.308.2.952s-.168.764-.396.764c-.224 0-.308-.084-.364-.14c-.252-.248-1.4-.52-1.872-.66c-.228.224-.52.712-.568.8c.48.084 1.216.496 1.36.58c.14.084.24 1.24.24 1.52c0 .228-.536.3-.8.3c-.04-.04-.12-.136-.12-.224c-.52-.4-1.716-.712-2.28-.776z");
}

.n2d5d5bri {
  fill: var(--svg-color--019f55, #019f55);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
