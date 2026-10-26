<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bf9of2e_o"/><path clip-rule="evenodd" class="fhporpb8k"/><path class="dexqwyboi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-duotone" /></template>
<style>
.bf9of2e_o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 19L4 19C2.3431 19 1 17.6569 1 16L1 6C1 4.3431 2.3431 3 4 3L17.4118 3C18.01 3 18.592 3.194 19.0706 3.5529C21.5442 5.4082 23 8.3198 23 11.4118L23 16C23 17.6569 21.6569 19 20 19L5 19Z");
  stroke: none;
}

.dexqwyboi {
  d: path("M9 18C9 19.1046 8.1046 20 7 20C5.8954 20 5 19.1046 5 18C5 16.8954 5.8954 16 7 16C8.1046 16 9 16.8954 9 18ZM19 18C19 19.1046 18.1046 20 17 20C15.8954 20 15 19.1046 15 18C15 16.8954 15.8954 16 17 16C18.1046 16 19 16.8954 19 18Z");
}

.fhporpb8k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 5L13 5L13 8L9 8L9 5ZM15 5L17.4118 5C17.5773 5 17.7382 5.0537 17.8706 5.1529C19.725 6.5437 20.8671 8.6852 20.9892 11L17.4142 11L15 8.5858L15 5ZM7 8L3 8L3 6C3 5.4477 3.4477 5 4 5L7 5L7 8Z");
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
