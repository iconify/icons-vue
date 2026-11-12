<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o6cb9_bxf"/><path class="p_iupj3wu"/><path class="hvt2a6e9c"/><path class="c2ccr1cfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:armchair-broken" /></template>
<style>
.c2ccr1cfe {
  d: path("M19 22V21M4 22V21");
}

.hvt2a6e9c {
  d: path("M6 10.2656V8.15385C6 5.85325 6 4.70296 6.48231 3.84615C6.79827 3.28485 7.25273 2.81874 7.8 2.49468C8.63538 2 9.75692 2 12 2C14.2431 2 15.3646 2 16.2 2.49468C16.7473 2.81874 17.2017 3.28485 17.5177 3.84615C18 4.70296 18 5.85325 18 8.15383V8.15385V10.2656");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o6cb9_bxf {
  stroke-linejoin: round;
  d: path("M2 15.8571C2 16.9195 2 17.4507 2.09402 17.8901C2.41456 19.3881 3.51119 20.5578 4.91555 20.8997C5.32748 21 5.82546 21 6.82143 21H17.1786C18.1745 21 18.6725 21 19.0845 20.8997C20.4888 20.5578 21.5854 19.3881 21.906 17.8901C22 17.4507 22 16.9195 22 15.8571V11.2456C22 10.0054 21.0574 9 19.8947 9C18.732 9 17.7895 10.0054 17.7895 11.2456V16.3333H16");
}

.p_iupj3wu {
  stroke-linejoin: round;
  d: path("M12 16.3333H6.21053V11.2456C6.21053 10.0054 5.26797 9 4.10526 9C2.94256 9 2 10.0054 2 11.2456V12");
}

</style>
