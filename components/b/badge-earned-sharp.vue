<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="d2m2a5b5t"/><circle class="d09_9tb0y"/><path class="bcbf4-3ov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:badge-earned-sharp" /></template>
<style>
.bcbf4-3ov {
  d: path("m8.8 16.75l1.65.75l.55.25l-.2.57l-.85 2.36l-.2.57l-.42-.42l-.66-.66l-.42-.42l-.59.13l-1.07.24l-.59.13l.31-.51l1.63-2.73l.31-.51zm6.4 0l-1.65.75l-.55.25l.2.57l.85 2.36l.2.57l.42-.42l.66-.66l.42-.42l.59.13l1.07.24l.59.13l-.31-.51l-1.63-2.73l-.31-.51z");
}

.d09_9tb0y {
  cx: 12px;
  cy: 8.75px;
  r: 2.5px;
}

.d2m2a5b5t {
  d: path("m12.72 3.54l.06.05l.72.55l.9-.02h.08l.9-.02l.26.86l.02.08l.26.86l.74.51l.07.05l.74.51l-.3.85l-.02.08l-.3.85l.3.85l.02.08l.3.85l-.74.51l-.07.05l-.74.51l-.26.86l-.02.08l-.26.86l-.9-.02h-.08l-.9-.02l-.72.55l-.06.05l-.72.54l-.72-.54l-.06-.05l-.72-.55l-.9.02h-.08l-.9.02l-.26-.86l-.02-.08l-.26-.86l-.74-.51l-.07-.05l-.74-.51l.3-.85l.02-.08l.3-.85l-.3-.85l-.02-.08l-.3-.85l.74-.51l.07-.05l.74-.51l.26-.86l.02-.08l.26-.86l.9.02h.08l.9.02l.72-.55l.06-.05L12 3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
