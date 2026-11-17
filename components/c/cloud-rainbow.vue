<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyd8fxb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rainbow" /></template>
<style>
.eyd8fxb7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.2146 8.16C7.0679 4.55 10.2907 2 14 2C18.4183 2 22 5.582 22 10V15M10.8013 7.598C11.5568 6.592 12.7417 6 14 6C16.2091 6 18 7.791 18 10V13.2M14 22H5C3.3431 22 2 20.657 2 19C2 17.343 3.3431 16 5 16C5 13.515 7.0147 11.5 9.5 11.5C11.9853 11.5 14 13.515 14 16C15.6569 16 17 17.343 17 19C17 20.657 15.6569 22 14 22Z");
}

</style>
