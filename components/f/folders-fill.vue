<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p6_k-ebum"/><path class="htjb-9byh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folders-fill" /></template>
<style>
.htjb-9byh {
  fill: currentColor;
  d: path("M7 5C7 3.3431 8.3431 2 10 2L11.1716 2C11.9672 2 12.7303 2.3161 13.2929 2.8787L14.1213 3.7071C14.3089 3.8946 14.5632 4 14.8284 4L19 4C20.6569 4 22 5.3431 22 7L22 14C22 15.6569 20.6569 17 19 17L10 17C8.3431 17 7 15.6569 7 14Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p6_k-ebum {
  d: path("M4 9.268C3.3812 9.6253 3 10.2855 3 11V19C3 20.1046 3.8954 21 5 21H14C14.7145 21 15.3747 20.6188 15.732 20");
}

</style>
