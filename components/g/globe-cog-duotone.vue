<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z4pr5qbyv"/><path class="agsjytb8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-cog-duotone" /></template>
<style>
.agsjytb8o {
  d: path("M20.6667 18C20.6667 19.4728 19.4728 20.6667 18 20.6667C16.5272 20.6667 15.3333 19.4728 15.3333 18C15.3333 16.5272 16.5272 15.3333 18 15.3333C19.4728 15.3333 20.6667 16.5272 20.6667 18ZM21.5417 18L22 18M20.5043 20.5043L20.8284 20.8284M18 21.5417L18 22M15.4957 20.5043L15.1716 20.8284M14.4583 18L14 18M15.4957 15.4957L15.1716 15.1716M18 14.4583L18 14M20.5043 15.4957L20.8284 15.1716");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z4pr5qbyv {
  stroke-opacity: 0.4;
  d: path("M10 21.8C5.4355 20.8734 2 16.8379 2 12C2 6.4772 6.4772 2 12 2C16.8379 2 20.8734 5.4355 21.8 10M2 12L10 12M10 19.2479C8.6667 16.9498 8 14.4749 8 12C8 8.5 9.3333 5 12 2C14.1579 4.4276 15.4426 7.1826 15.8544 10");
}

</style>
