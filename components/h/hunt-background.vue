<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="u3zubo0gd"/><path class="xnisjitfk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hunt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u3zubo0gd {
  fill: var(--svg-color--fb6f6e, #fb6f6e);
  d: path("M24 0H0v24h24z");
}

.xnisjitfk {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.886 4.914a.914.914 0 1 1 1.828 0V8.81a4.114 4.114 0 0 1 6.4 3.42v4.114a.915.915 0 0 1-1.828 0V12.23a2.286 2.286 0 1 0-4.572 0v4.114a.914.914 0 0 1-1.828 0zm1.828 14.172a.914.914 0 1 1-1.828 0a.914.914 0 0 1 1.828 0M15.2 20a.914.914 0 1 0 0-1.828a.914.914 0 0 0 0 1.828");
}

</style>
