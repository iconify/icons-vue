<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cqx7p_7kr"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:iframe-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.cqx7p_7kr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.4142 17.4142C17.0523 17.7762 16.5523 18 16 18L8 18C6.8954 18 6 17.1046 6 16L6 14C6 12.8954 6.8954 12 8 12L12 12ZM20.8285 20.8285C20.1046 21.5523 19.1046 22 18 22L6 22C3.7909 22 2 20.2092 2 18L2 9L2 6C2 4.8955 2.4477 3.8955 3.1716 3.1716L10 10L4 10L4 18C4 19.1046 4.8954 20 6 20L18 20C18.5523 20 19.0523 19.7762 19.4142 19.4142ZM20.2929 16.0503L20 15.7574L20 10L14.2426 10L7.9498 3.7071C7.7688 3.5261 7.6569 3.2761 7.6569 3C7.6569 2.4477 8.1046 2 8.6569 2L12 2L18 2C20.2092 2 22 3.7909 22 6L22 9L22 15.3431C22 15.8954 21.5523 16.3431 21 16.3431C20.7239 16.3431 20.4739 16.2312 20.2929 16.0503Z");
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
