<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fi1yetb4b"/><path class="pf5q-wlbm"/><path class="p3v9x98ar"/><path class="j-a1kqp-o"/><path class="pxxsney2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-2-line-duotone" /></template>
<style>
.fi1yetb4b {
  d: path("M10 20H14C17.7712 20 19.6569 20 20.8284 18.8284C22 17.6569 22 15.7712 22 12C22 8.22876 22 6.34315 20.8284 5.17157C19.6569 4 17.7712 4 14 4H10C6.22876 4 4.34315 4 3.17157 5.17157C2 6.34315 2 8.22876 2 12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-a1kqp-o {
  d: path("M2 10L22 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.p3v9x98ar {
  d: path("M8 13.5H6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pf5q-wlbm {
  d: path("M10 16.5H6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pxxsney2w {
  d: path("M16 17C15.0572 17 14.5858 17 14.2929 16.7071C14 16.4142 14 15.9428 14 15C14 14.0572 14 13.5858 14.2929 13.2929C14.5858 13 15.0572 13 16 13C16.9428 13 17.4142 13 17.7071 13.2929C18 13.5858 18 14.0572 18 15C18 15.9428 18 16.4142 17.7071 16.7071C17.4142 17 16.9428 17 16 17Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
