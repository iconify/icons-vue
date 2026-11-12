<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pqx2-oyar"/><path class="piz2n9t2p"/><path class="b4_g5c43k"/><path class="iq-a2cc9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-heart-minimalistic-broken" /></template>
<style>
.b4_g5c43k {
  stroke-linejoin: round;
  d: path("M13 11.7148C13 13.4674 15.1633 15.3304 16.4901 16.3082C16.9442 16.643 17.1713 16.8103 17.5 16.8103C17.8287 16.8103 18.0558 16.643 18.5099 16.3083C19.8367 15.3304 22 13.4674 22 11.7148C22 9.03759 19.5249 8.03807 17.5 10.1062C15.4751 8.03807 13 9.03759 13 11.7148Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iq-a2cc9w {
  d: path("M20 6L9.5 6M3 6L5.25 6");
}

.piz2n9t2p {
  d: path("M9 11H3");
}

.pqx2-oyar {
  d: path("M10 16H3");
}

</style>
