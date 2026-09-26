<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ozqsggbsj"/><path class="v7fs5fzgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-u-turn-right-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozqsggbsj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C6.0629 1 1 6.0629 1 12C1 17.937 6.0629 23 12 23C17.937 23 23 17.937 23 12C23 6.0629 17.937 1 12 1Z");
  stroke: none;
}

.v7fs5fzgi {
  d: path("M15.9167 10.5L11.0797 10.5C9.3788 10.5 8 11.8431 8 13.5C8 15.1569 9.3788 16.5 11.0797 16.5L13.1063 16.5M12.8375 7.1909L16 10.5L12.8375 13.8091");
}

</style>
