<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bwh55u1jl"/><circle class="d09_9tb0y"/><path class="fllxt_fng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:badge-earned" /></template>
<style>
.bwh55u1jl {
  d: path("m12.72 3.54l.06.05q.72.55 1.62.53h.08q.9-.02 1.16.84l.02.08q.26.86 1 1.37l.07.05q.74.51.44 1.36l-.02.08q-.3.85 0 1.7l.02.08q.3.85-.44 1.36l-.07.05q-.74.51-1 1.37l-.02.08q-.26.86-1.16.84h-.08q-.9-.02-1.62.53l-.06.05q-.72.54-1.44 0l-.06-.05q-.72-.55-1.62-.53h-.08q-.9.02-1.16-.84l-.02-.08q-.26-.86-1-1.37l-.07-.05q-.74-.51-.44-1.36l.02-.08q.3-.85 0-1.7l-.02-.08q-.3-.85.44-1.36l.07-.05q.74-.51 1-1.37l.02-.08q.26-.86 1.16-.84h.08q.9.02 1.62-.53l.06-.05q.72-.54 1.44 0");
}

.d09_9tb0y {
  cx: 12px;
  cy: 8.75px;
  r: 2.5px;
}

.fllxt_fng {
  d: path("m8.8 16.75l1.65.75q.55.25.35.82l-.85 2.36q-.2.57-.62.15l-.66-.66q-.42-.42-1.01-.29l-1.07.24q-.59.13-.28-.38l1.63-2.73q.31-.51.86-.26m6.4 0l-1.65.75q-.55.25-.35.82l.85 2.36q.2.57.62.15l.66-.66q.42-.42 1.01-.29l1.07.24q.59.13.28-.38l-1.63-2.73q-.31-.51-.86-.26");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
