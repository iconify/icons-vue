<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kyrexbblq"/><path class="r2jnhoaem"/><path class="rsgshebrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cabin" /></template>
<style>
.kyrexbblq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20.5v-8.25q0-.75-.62-.75q-.63 0-.05-.47l8.09-6.56q.58-.47 1.16 0l8.09 6.56q.58.47-.04.47q-.63 0-.63.75v8.25q0 .75-.75.75H4.75q-.75 0-.75-.75m0-5.75h5m6 0h5M4 18h5m6 0h5");
}

.r2jnhoaem {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.25h.01");
}

.rsgshebrg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 21.25v-5.5h4v5.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
