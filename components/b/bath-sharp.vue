<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of-vur_2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bath-sharp" /></template>
<style>
.of-vur_2c {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11L3 19L21 19L21 11M1 11L23 11M8 19L6.7236 21.5528M16 19L17.2764 21.5528M3 11L3 6C3 4.3431 4.3431 3 6 3C7.0463 3 8.0169 3.5451 8.5615 4.4384M7.2071 5.7929L10.2929 2.7071");
}

</style>
