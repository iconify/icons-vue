<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q4ufz_ber"/><path class="ex19bob7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-rounded-line-duotone" /></template>
<style>
.ex19bob7r {
  d: path("M3.08289 10.5032C2.27659 11.373 2 12.6127 2 13.8504C2 15.9103 3.78158 17.4151 5.6072 16.8973L6.9469 16.5173C8.15591 16.1744 9 14.9826 9 13.6185M20.9171 10.5032C21.7234 11.373 22 12.6127 22 13.8504C22 15.9103 20.2184 17.4151 18.3928 16.8973L17.0531 16.5173C15.8441 16.1744 15 14.9826 15 13.6185");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q4ufz_ber {
  d: path("M3.08289 10.5034C2.27659 11.3733 2 12.6129 2 13.8506C2 15.9105 3.78158 17.4153 5.6072 16.8975L6.9469 16.5175C8.15591 16.1746 9 14.9828 9 13.6187C9 13.6187 9 11.9639 12 11.9639C15 11.9639 15 13.6187 15 13.6187C15 14.9828 15.8441 16.1746 17.0531 16.5175L18.3928 16.8975C20.2184 17.4153 22 15.9105 22 13.8506C22 12.6129 21.7234 11.3733 20.9171 10.5034C19.5598 9.03911 16.8069 7 12.0001 7C7.19334 7 4.44023 9.03911 3.08289 10.5034Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
