<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="zjw_rp46h"/><path class="lydvrx62r"/><path class="sleg5gorn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:birthday-crown" /></template>
<style>
.lydvrx62r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.16 13.12l.36.83q.16.37.55.41l.91.08q.4.04.1.3l-.69.6q-.3.27-.21.66l.2.88q.09.39-.25.19l-.79-.47q-.34-.2-.68 0l-.79.47q-.34.2-.25-.19l.2-.88q.09-.39-.21-.66l-.69-.6q-.3-.26.1-.3l.91-.08q.39-.04.55-.41l.36-.83q.16-.37.32 0");
}

.sleg5gorn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.5 5h.01M12 3.75h.01M20.5 5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zjw_rp46h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.17 8.6l3.16 2.8q.67.6 1.2-.13l2.94-4.04q.53-.73 1.06 0l2.94 4.04q.53.73 1.2.13l3.16-2.8q.67-.6.56.29l-1.28 10.22Q19 20 18.1 20H5.9q-.9 0-1.01-.89L3.61 8.89Q3.5 8 4.17 8.6");
}

</style>
