<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="edkibiblc"/><path class="fbschg62a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-left-duotone-regular" /></template>
<style>
.edkibiblc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 5 -7 7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fbschg62a {
  d: path("m15 5 -7 7 7 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
