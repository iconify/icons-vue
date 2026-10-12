<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hp5knsbpi"/><path clip-rule="evenodd" class="clzhx63lw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-simple" /></template>
<style>
.clzhx63lw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 3.5C13.5 4.3284 12.8284 5 12 5C11.1716 5 10.5 4.3284 10.5 3.5C10.5 2.6716 11.1716 2 12 2C12.8284 2 13.5 2.6716 13.5 3.5ZM10.5 14.5C10.5 15.3284 9.8284 16 9 16C8.1716 16 7.5 15.3284 7.5 14.5C7.5 13.6716 8.1716 13 9 13C9.8284 13 10.5 13.6716 10.5 14.5ZM16.5 14.5C16.5 15.3284 15.8284 16 15 16C14.1716 16 13.5 15.3284 13.5 14.5C13.5 13.6716 14.1716 13 15 13C15.8284 13 16.5 13.6716 16.5 14.5Z");
  stroke: none;
}

.hp5knsbpi {
  d: path("M4 12C4 9.7909 5.7909 8 8 8L16 8C18.2091 8 20 9.7909 20 12L20 17C20 19.2091 18.2091 21 16 21L8 21C5.7909 21 4 19.2091 4 17L4 12ZM12 8L12 3.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
