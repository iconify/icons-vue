<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8b2b6ksg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hourglass-start" /></template>
<style>
.p8b2b6ksg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 2L20 2M4 22L20 22M6 2L6 6.0633C6 6.6568 6.2636 7.2197 6.7196 7.5997L12 12L17.2804 7.5997C17.7364 7.2197 18 6.6568 18 6.0633L18 2L6 2ZM6 22L6 17.9367C6 17.3432 6.2636 16.7803 6.7196 16.4003L12 12L17.2804 16.4003C17.7364 16.7803 18 17.3432 18 17.9367L18 22L6 22ZM6 6L18 6");
}

</style>
