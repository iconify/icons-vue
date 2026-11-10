<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="okhy_ybad"/><path class="wqxw53brg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-sensitive-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.okhy_ybad {
  stroke-opacity: 0.4;
  d: path("M2 18.001L3.7857 13.001L6.0583 6.668C6.3743 5.783 7.6257 5.783 7.9417 6.668L10.2143 13.001L12 18.001M10.2143 13.001H3.7857");
}

.wqxw53brg {
  d: path("M22 15C22 16.657 20.6569 18 19 18C17.3431 18 16 16.657 16 15C16 13.343 17.3431 12 19 12C20.6569 12 22 13.343 22 15ZM22 15V11M22 15V18");
}

</style>
