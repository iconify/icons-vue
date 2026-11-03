<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dn6l1pbun"/><path class="glvpx1ysv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:desk-duotone" /></template>
<style>
.dn6l1pbun {
  stroke-opacity: 0.4;
  d: path("M2 12L22 12M7 8L7 12L4 12L4 22M20 12L20 22M20 19L4 19");
}

.glvpx1ysv {
  fill: currentColor;
  d: path("M7 9L4.6404 9C3.812 9 3.1404 8.3284 3.1404 7.5C3.1404 7.3773 3.1554 7.2551 3.1852 7.1362L4.4352 2.1359C4.6024 1.4683 5.2022 1 5.8904 1L8.1096 1C8.7979 1.0001 9.3978 1.4685 9.5648 2.1362L10.8148 7.1362C10.8446 7.2551 10.8596 7.3773 10.8596 7.5C10.8596 8.3284 10.188 9 9.3596 9L7 9Z");
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
