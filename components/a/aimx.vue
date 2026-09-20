<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGrx5wycYO)" class="ff4tbwb7g"/><defs><linearGradient id="SVGrx5wycYO" x1="5.642" x2="18.072" y1="6.147" y2="18.795" gradientUnits="userSpaceOnUse"><stop class="v6co0sbfj"/><stop offset="1" class="hv4sh8eqf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aimx" /></template>
<style>
.ff4tbwb7g {
  d: path("m10.628 3.915l-.084.064c-1.223 1.274-.457 4.125-1.126 6.37c-.63 2.124-3.867 3.333-5.238 4.633a3.212 3.212 0 1 0 4.408 4.646H8.6a2.4 2.4 0 0 0 .553-.856l.032-.09v-.032a3 3 0 0 0 .129-.399c.618-2.265.232-6.113.76-7.49c.662-1.73 1.859-2.606 2.856-3.565c.689-.656 1.126-1.351 1.023-2.11V5.04a1.93 1.93 0 0 0-1.568-1.698a1.9 1.9 0 0 0-.82.025c-.36.09-.688.283-.939.547m6.511 14.844a1.931 1.931 0 1 0 3.863 0a1.931 1.931 0 0 0-3.863 0");
}

.ft5dv1b6b {
  fill: none;
}

.hv4sh8eqf {
  stop-color: var(--svg-color--00a790, #00a790);
}

.v6co0sbfj {
  stop-color: var(--svg-color--135554, #135554);
}

</style>
