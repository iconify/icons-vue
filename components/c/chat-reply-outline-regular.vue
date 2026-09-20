<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x_lkvk_2h"/><path class="ebuv7_btt"/><path class="usozqs3sa"/><path class="g03lyybyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chat-reply-outline-regular" /></template>
<style>
.ebuv7_btt {
  d: path("M7 17v3l3 -3");
}

.g03lyybyp {
  d: path("M11 7.5 8.5 10l2.5 2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.usozqs3sa {
  d: path("M8.5 10H17");
}

.x_lkvk_2h {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
