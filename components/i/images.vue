<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kbxfhb-6c"/><path class="ed465-r6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:images" /></template>
<style>
.ed465-r6k {
  fill: currentColor;
  d: path("M12 7C12 7.5522847498 11.5522847498 8 11 8C10.4477152502 8 10 7.5522847498 10 7C10 6.4477152502 10.4477152502 6 11 6C11.5522847498 6 12 6.4477152502 12 7Z");
  stroke: none;
}

.kbxfhb-6c {
  d: path("M3 8V18C3 19.6569 4.3431 21 6 21H16M10 3H18C19.6569 3 21 4.3431 21 6V14C21 15.6569 19.6569 17 18 17H10C8.3431 17 7 15.6569 7 14V6C7 4.3431 8.3431 3 10 3ZM7 14L14.3292 10.3354C14.7515 10.1243 15.2485 10.1243 15.6708 10.3354L21 13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
