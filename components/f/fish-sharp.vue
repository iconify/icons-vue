<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dlxrbxmvp"/><path clip-rule="evenodd" class="wsnlq1w_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fish-sharp" /></template>
<style>
.dlxrbxmvp {
  d: path("M17 9.42L12.245 5.25C12.063 5.09 11.829 5 11.586 5C11.124 5 10.722 5.32 10.614 5.77L9.5 10.41M7.415 11.4C7.529 11.44 7.65 11.46 7.773 11.46C8.016 11.46 8.25 11.38 8.433 11.21C10.057 9.79 12.145 9 14.308 9C17.244 9 19.99 10.45 21.65 12.87C21.878 13.2 22 13.6 22 14C22 14.4 21.878 14.8 21.65 15.13C19.99 17.55 17.244 19 14.308 19C12.145 19 10.057 18.21 8.433 16.79C8.25 16.62 8.016 16.54 7.773 16.54C7.65 16.54 7.529 16.56 7.415 16.6L3.357 18.16C3.243 18.2 3.122 18.22 3 18.22C2.448 18.22 2 17.77 2 17.22C2 16.94 2.116 16.68 2.32 16.49L4.211 14.73C4.415 14.54 4.53 14.28 4.53 14C4.53 13.72 4.415 13.46 4.211 13.27L2.32 11.51C2.116 11.32 2 11.06 2 10.78C2 10.23 2.448 9.78 3 9.78C3.122 9.78 3.243 9.8 3.357 9.84L7.415 11.4Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wsnlq1w_a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 14C18 14.55 17.552 15 17 15C16.448 15 16 14.55 16 14C16 13.45 16.448 13 17 13C17.552 13 18 13.45 18 14Z");
  stroke: none;
}

</style>
