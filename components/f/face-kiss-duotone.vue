<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qpf542--f"/><path class="cq0vcebni"/><path clip-rule="evenodd" class="hwv1e0bme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-kiss-duotone" /></template>
<style>
.cq0vcebni {
  d: path("M9 10V11M15 10V11");
}

.hwv1e0bme {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.4577 20.817C14.7194 20.106 14 19.163 14 17.917C14 17.08 14.3736 16.341 14.9409 15.823C15.5068 15.306 16.2728 15 17.1 15C17.6083 15 18.078 15.118 18.5 15.324C18.922 15.118 19.3917 15 19.9 15C20.7272 15 21.4932 15.306 22.0591 15.823C22.6264 16.341 23 17.08 23 17.917C23 19.163 22.2806 20.106 21.5423 20.817C21.165 21.18 20.7429 21.52 20.3345 21.838C19.9115 22.167 19.5197 22.46 19.131 22.776C18.9527 22.921 18.7299 23 18.5 23C18.2701 23 18.0473 22.921 17.869 22.776C17.4803 22.46 17.0885 22.167 16.6655 21.838C16.2571 21.52 15.835 21.18 15.4577 20.817ZM12 16.5C12 17.328 11.3284 18 10.5 18C9.6716 18 9 17.328 9 16.5C9 15.672 9.6716 15 10.5 15C11.3284 15 12 15.672 12 16.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qpf542--f {
  stroke-opacity: 0.4;
  d: path("M12.349 21.994C12.2327 21.998 12.1164 22 12 22C6.4772 22 2 17.523 2 12C2 6.477 6.4772 2 12 2C17.5228 2 22 6.477 22 12C22 12.116 21.998 12.233 21.9939 12.349");
}

</style>
