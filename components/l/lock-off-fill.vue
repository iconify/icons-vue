<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="wmownjpqc"/><path class="xwbsmabum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-off-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wmownjpqc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.6465 20.6465C20.0188 22.0343 18.6222 23 17 23L7 23C4.7909 23 3 21.2091 3 19L3 13C3 10.7909 4.7909 9 7 9L9 9ZM15.6569 9L17 9C19.2091 9 21 10.7909 21 13L21 14.3431C21 14.8954 20.5523 15.3431 20 15.3431C19.7239 15.3431 19.4739 15.2312 19.2929 15.0503L14.9498 10.7071C14.7688 10.5262 14.6569 10.2762 14.6569 10C14.6569 9.4477 15.1046 9 15.6569 9Z");
  stroke: none;
}

.xwbsmabum {
  d: path("M7.5 10L7.5 7.5M8.8974 3.2406C9.7047 2.4719 10.7973 2 12 2C14.4853 2 16.5 4.0147 16.5 6.5L16.5 10M2 2L22 22");
}

</style>
