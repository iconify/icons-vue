<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yjt4258yu"/><path class="kl6ms1bhr"/><path class="sdppemtic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-unknown" /></template>
<style>
.kl6ms1bhr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5M10 12.5a2 2 0 1 1 2.75 1.85c-.45.2-.75.6-.75 1.1v.3");
}

.sdppemtic {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yjt4258yu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75h-6.5a2.5 2.5 0 0 0-2.5 2.5v13.5a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5V8.25Z");
}

</style>
