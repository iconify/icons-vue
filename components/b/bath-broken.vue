<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z7e54ab2u"/><path class="usqinzbwd"/><path class="j7lpo2bzk"/><path class="dri67ubou"/><path class="vz6h-5b6e"/><path class="x-f9gbc6v"/><path class="gg65u8b7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bath-broken" /></template>
<style>
.dri67ubou {
  d: path("M2 12H14M18 12H22");
}

.gg65u8b7q {
  d: path("M7.97885 4.44713L7.59973 3.49934C7.23752 2.59379 6.36047 2 5.38516 2C4.06787 2 3 3.06787 3 4.38516V13");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7lpo2bzk {
  d: path("M18 20L19 22");
}

.usqinzbwd {
  d: path("M6 20L5 22");
}

.vz6h-5b6e {
  d: path("M12.3065 6.17554L6.3457 8.74162");
}

.x-f9gbc6v {
  d: path("M6.34543 8.74152C6.03547 7.95489 6.01649 7.04299 6.36196 6.19229C6.6867 5.39262 7.27566 4.78934 7.9787 4.4471C8.77147 4.06116 9.70961 4.00734 10.5772 4.37797C11.3956 4.72762 11.9965 5.38898 12.3065 6.17562");
}

.z7e54ab2u {
  d: path("M12 20.5C12.6493 20.5 13.364 20.4831 14.0982 20.4555C14.3558 20.4458 14.4845 20.441 14.7053 20.4186C17.983 20.0867 20.7773 17.1854 20.9859 13.8977C21 13.6762 21 13.4784 21 13.0827C21 13.0059 21 12.9675 20.9979 12.9351C20.9653 12.4339 20.5661 12.0347 20.0649 12.0021C20.0325 12 19.9941 12 19.9173 12M4.08268 12C4.00591 12 3.96752 12 3.93511 12.0021C3.43395 12.0347 3.0347 12.4339 3.00211 12.9351C3 12.9675 3 13.0059 3 13.0827C3 13.4784 3 13.6762 3.01406 13.8977C3.19458 16.742 5.31032 19.2971 8 20.1495");
}

</style>
