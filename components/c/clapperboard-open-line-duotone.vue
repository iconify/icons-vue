<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l6fn0fb1j"/><path class="ldjg42xkf"/><path class="mb74phb2i"/><path class="jokz056ng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-open-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jokz056ng {
  d: path("M8.42209 4.62381L7.78433 9.97108");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.l6fn0fb1j {
  d: path("M4 11H16C17.8856 11 18.8284 11 19.4142 11.5858C20 12.1716 20 13.1144 20 15V16C20 18.8284 20 20.2426 19.1213 21.1213C18.2426 22 16.8284 22 14 22H10C7.17157 22 5.75736 22 4.87868 21.1213C4 20.2426 4 18.8284 4 16V11Z");
}

.ldjg42xkf {
  d: path("M4.00079 10.9997L18.2482 7.18214C18.4726 7.12201 18.5848 7.09194 18.6732 7.04838C19.0359 6.86949 19.2552 6.4897 19.2287 6.0861C19.2223 5.98782 19.1922 5.87562 19.1321 5.65121C18.9517 4.97797 18.8615 4.64136 18.7308 4.37635C18.1941 3.2881 17.0548 2.63028 15.844 2.70964C15.5491 2.72897 15.2125 2.81916 14.5393 2.99956L7.53633 4.87599C5.73079 5.35979 4.82802 5.60168 4.25961 6.17009C3.88724 6.54246 3.61945 7.00629 3.48316 7.51495C3.2751 8.29141 3.517 9.19418 4.00079 10.9997Z");
}

.mb74phb2i {
  d: path("M14.7014 2.94147L14.0636 8.28874");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
