<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i7nxzzb0y"/><path class="j6eqvjb3b"/><path clip-rule="evenodd" class="mqz8vbcef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-frown-duotone" /></template>
<style>
.i7nxzzb0y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 7H17C19.2092 7 21 8.791 21 11V18C21 20.209 19.2092 22 17 22H7C4.7908 22 3 20.209 3 18V11C3 8.791 4.7908 7 7 7H12Z");
  stroke: none;
}

.j6eqvjb3b {
  d: path("M12 8V3.5M2 14.5H4M22 14.5H20M9 17C10 16 11 15.5 12 15.5C13 15.5 14 16 15 17");
}

.mqz8vbcef {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 3.5C13.5 4.328 12.8284 5 12 5C11.1716 5 10.5 4.328 10.5 3.5C10.5 2.672 11.1716 2 12 2C12.8284 2 13.5 2.672 13.5 3.5ZM10 12C10 12.552 9.5523 13 9 13C8.4477 13 8 12.552 8 12C8 11.448 8.4477 11 9 11C9.5523 11 10 11.448 10 12ZM16 12C16 12.552 15.5523 13 15 13C14.4477 13 14 12.552 14 12C14 11.448 14.4477 11 15 11C15.5523 11 16 11.448 16 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
