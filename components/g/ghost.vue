<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltcmawmty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ghost" /></template>
<style>
.ltcmawmty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9V10M15 9V10M4 21V10C4 5.58 7.5817 2 12 2C16.4183 2 20 5.58 20 10V21L19.7687 20.54C19.2976 19.6 18.3346 19 17.2812 19C15.7452 19 14.5 20.25 14.5 21.78V22V21.5C14.5 20.12 13.3807 19 12 19C10.6193 19 9.5 20.12 9.5 21.5V22V21.78C9.5 20.25 8.2548 19 6.7189 19C5.6654 19 4.7024 19.6 4.2313 20.54L4 21Z");
}

</style>
