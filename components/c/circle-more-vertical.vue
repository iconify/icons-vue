<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tx_ah59as"/><path class="bocf8ab2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-more-vertical" /></template>
<style>
.bocf8ab2v {
  fill: currentColor;
  d: path("M12 6C12.7364 6 13.3333 6.5969 13.3333 7.3333C13.3333 8.0697 12.7364 8.6666 12 8.6666C11.2636 8.6666 10.6667 8.0697 10.6667 7.3333C10.6667 6.5969 11.2636 6 12 6ZM12 10.6667C12.7364 10.6667 13.3333 11.2636 13.3333 12C13.3333 12.7364 12.7364 13.3333 12 13.3333C11.2636 13.3333 10.6667 12.7364 10.6667 12C10.6667 11.2636 11.2636 10.6667 12 10.6667ZM12 15.3334C12.7364 15.3334 13.3333 15.9303 13.3333 16.6667C13.3333 17.4031 12.7364 18 12 18C11.2636 18 10.6667 17.4031 10.6667 16.6667C10.6667 15.9303 11.2636 15.3334 12 15.3334Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tx_ah59as {
  d: path("M12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2Z");
}

</style>
