<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tmhmkfbhb"/><path class="n9y3s2jbt"/><path class="w4giizb1e"/><path class="q5bla5t6u"/><path class="v1y9d1bvi"/><path class="e9wqqffiv"/><path class="h26hx985n"/><path class="uy1fi6wpd"/><path class="bzfuiwbgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:adhesive-plaster-broken" /></template>
<style>
.bzfuiwbgo {
  stroke-linejoin: round;
  d: path("M8.75 8.75H8.7501");
}

.e9wqqffiv {
  stroke-linejoin: round;
  d: path("M15.2969 13.4204H15.297");
}

.h26hx985n {
  stroke-linejoin: round;
  d: path("M13.4297 15.2798H13.4298");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n9y3s2jbt {
  d: path("M11.9997 17.8579L9.07078 20.7868C7.45317 22.4044 4.83052 22.4044 3.21291 20.7868C2.9709 20.5448 2.76509 20.2803 2.5955 20M6.14184 12L3.21291 14.9289C2.89051 15.2513 2.63236 15.6137 2.43848 16M11.9997 6.14214L14.9286 3.2132C16.5462 1.5956 19.1689 1.5956 20.7865 3.2132C22.4041 4.83081 22.4041 7.45346 20.7865 9.07107L17.8576 12");
}

.q5bla5t6u {
  stroke-linejoin: round;
  d: path("M9.7168 11.5688H9.7169");
}

.tmhmkfbhb {
  d: path("M13.5 7.64214L9.07107 3.2132C7.45346 1.5956 4.83081 1.5956 3.2132 3.2132C1.5956 4.83081 1.5956 7.45346 3.2132 9.07107L14.9289 20.7868C16.5465 22.4044 19.1692 22.4044 20.7868 20.7868C22.4044 19.1692 22.4044 16.5465 20.7868 14.9289L16.4289 10.5711");
}

.uy1fi6wpd {
  stroke-linejoin: round;
  d: path("M16.2158 16.2029H16.2159");
}

.v1y9d1bvi {
  stroke-linejoin: round;
  d: path("M12.5 12.5H12.5001");
}

.w4giizb1e {
  stroke-linejoin: round;
  d: path("M11.5732 9.71191H11.5733");
}

</style>
