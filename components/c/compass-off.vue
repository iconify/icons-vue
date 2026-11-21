<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k86o2ibux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:compass-off" /></template>
<style>
.k86o2ibux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.3456 2.6888C9.4776 2.2442 10.7103 2 12 2C17.5228 2 22 6.4772 22 12C22 13.2897 21.7558 14.5224 21.3112 15.6544M19.0711 19.0711C17.2614 20.8807 14.7614 22 12 22C6.4772 22 2 17.5228 2 12C2 9.2386 3.1193 6.7386 4.9289 4.9289M2 2L22 22M14.3331 14.3331C14.1164 14.5498 13.8499 14.7167 13.5513 14.8162L8.89737 16.3675C8.11561 16.6281 7.37187 15.8844 7.63246 15.1026L9.18377 10.4487C9.2833 10.1501 9.4502 9.8836 9.6669 9.6669");
}

</style>
