<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="q45s06htc"/><path class="dw50e241k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-nand-fill" /></template>
<style>
.dw50e241k {
  d: path("M18 12C18 10.8954 18.8954 10 20 10C21.1046 10 22 10.8954 22 12C22 13.1046 21.1046 14 20 14C18.8954 14 18 13.1046 18 12ZM2 8L7 8M2 16L7 16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q45s06htc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.6569 6.3431C18.1035 7.7898 19 9.7911 19 12C19 16.4183 15.4183 20 11 20L9 20C7.3431 20 6 18.6569 6 17L6 7C6 5.3431 7.3431 4 9 4L11 4C13.2089 4 15.2102 4.8965 16.6569 6.3431Z");
  stroke: none;
}

</style>
