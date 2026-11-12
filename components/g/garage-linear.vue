<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xpzbxokqs"/><path class="o1ddb9b2p"/><path class="gf8hoxv3z"/><path class="nv6qhg7zp"/><path class="lbfuos7ub"/><path class="km125xbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:garage-linear" /></template>
<style>
.gf8hoxv3z {
  d: path("M10 9H14");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.km125xbck {
  d: path("M18 22V16C18 14.1144 18 13.1716 17.4142 12.5858C16.8284 12 15.8856 12 14 12H10C8.11438 12 7.17157 12 6.58579 12.5858C6 13.1716 6 14.1144 6 16V22");
}

.lbfuos7ub {
  d: path("M9 18.5H15");
}

.nv6qhg7zp {
  d: path("M9 15.5H15");
}

.o1ddb9b2p {
  d: path("M3 22V11.3472C3 10.4903 3.36644 9.67426 4.00691 9.10496L10.0069 3.77163C11.1436 2.76126 12.8564 2.76126 13.9931 3.77163L19.9931 9.10496C20.6336 9.67426 21 10.4903 21 11.3472V22");
}

.xpzbxokqs {
  d: path("M22 22L2 22");
}

</style>
