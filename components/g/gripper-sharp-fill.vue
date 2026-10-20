<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="olfib4fzh"/><path class="rlgdf0bym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gripper-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.olfib4fzh {
  fill: currentColor;
  d: path("M16 10C16 12.2091 14.2091 14 12 14C9.7909 14 8 12.2091 8 10C8 7.7909 9.7909 6 12 6C14.2091 6 16 7.7909 16 10Z");
  stroke: none;
}

.rlgdf0bym {
  d: path("M12 1L12 7M14.4575 11.7207L20 16.0638L15.7027 22.4412M9.5425 11.7207L4 16.0638L8.2973 22.4412");
}

</style>
