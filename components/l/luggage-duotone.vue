<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="m9l9qcceu"/><path class="qjt3n5bdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:luggage-duotone" /></template>
<style>
.m9l9qcceu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M9.2808 5L14.7192 5L14.4086 3.7575C14.2973 3.3123 13.8973 3 13.4384 3L10.5616 3C10.1027 3 9.7027 3.3123 9.5914 3.7575L9.2808 5ZM16.7808 5L17 5C18.6569 5 20 6.3431 20 8L20 18C20 19.6569 18.6569 21 17 21L7 21C5.3431 21 4 19.6569 4 18L4 8C4 6.3431 5.3431 5 7 5L7.2192 5L7.6512 3.2723C7.9851 1.9369 9.185 1 10.5616 1L13.4384 1C14.815 1 16.015 1.9369 16.3488 3.2724L16.7808 5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qjt3n5bdi {
  d: path("M7 11L17 11M7 20L7 22M17 20L17 22");
}

</style>
