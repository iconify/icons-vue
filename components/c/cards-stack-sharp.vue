<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hw7mphrys"/><path class="f-zrabjwc"/><path class="beg9c9ble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cards-stack-sharp" /></template>
<style>
.beg9c9ble {
  d: path("m10.07 10.88l2.11 2.49l.32.38l-.32.38l-2.11 2.49l-.32.38l-.32-.38l-2.11-2.49l-.32-.38l.32-.38l2.11-2.49l.32-.38z");
}

.f-zrabjwc {
  d: path("M3.25 6.25h13v15h-13z");
}

.hw7mphrys {
  d: path("M6.75 6.25v-3.5h14.5v16.5h-5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
