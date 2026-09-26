<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_toq0bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-right-sharp" /></template>
<style>
.c_toq0bkr {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 18L21 18M17.7071 21.2929L21 18L17.7071 14.7071M6 14L6 3M9.2929 6.2929L6 3L2.7071 6.2929M12 3L15.3333 3M17.3333 3L21 3L21 6.6667M21 8.6667L21 12");
}

</style>
