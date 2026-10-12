<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="e-4z4k0az"/><path class="yzncb0r_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:boomerang" /></template>
<style>
.e-4z4k0az {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.68 5.3l7.64 11.9q.68 1.05-.39 1.69l-.36.22q-1.07.64-1.8-.37l-5.04-6.98q-.73-1.01-1.46 0l-5.04 6.98q-.73 1.01-1.8.37l-.36-.22Q3 18.25 3.68 17.2l7.64-11.9q.68-1.05 1.36 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yzncb0r_t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.7 15.5h.01m10.59 0h.01M12 7.75h.01");
}

</style>
