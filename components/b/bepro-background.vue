<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t08of6e6i"/><path class="jp5z-r5yd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bepro-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jp5z-r5yd {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4a8 8 0 1 1 0 16A7.995 7.995 0 0 1 4.758 8.61A3.44 3.44 0 0 0 8.14 11.5H9V10h-.865c-.915.015-1.695-.985-1.71-1.89v-.02c-.01-.93.795-1.574 1.7-1.59c.93-.01 1.85.686 1.87 1.6v5.11c0 1.855 1.125 3.3 3 3.29c1.94-.006 3.5-1.56 3.5-3.4A3.15 3.15 0 0 0 13.24 10h-.74v1.5h.745A1.785 1.785 0 0 1 15 13.2v.02A1.84 1.84 0 0 1 13.256 15c-.885.005-1.74-.89-1.755-1.79V8.1c0-.93-.275-1.744-.94-2.41a3.5 3.5 0 0 0-1.855-.954A7.56 7.56 0 0 1 12.001 4");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t08of6e6i {
  fill: var(--svg-color--4250e4, #4250e4);
  d: path("M24 0H0v24h24z");
}

</style>
