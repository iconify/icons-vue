<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o_a3wxbvc"/><path class="vlin9tbyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hub-connected" /></template>
<style>
.o_a3wxbvc {
  d: path("M3 8.25a8.5 4.5 0 1 0 17 0a8.5 4.5 0 1 0-17 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vlin9tbyz {
  d: path("M3 8.25v3.5q0 .11.01.221q.01.11.031.22t.051.219q.031.11.071.218q.041.108.092.215q.05.108.111.213q.061.106.131.21t.15.206t.169.202t.188.197q.098.098.205.192q.108.095.224.187q.115.092.24.181q.124.088.256.174q.133.085.273.167t.288.16q.147.078.302.152q.154.074.316.145q.161.07.329.135q.167.066.341.128q.173.061.352.118t.363.109t.373.099t.381.089t.389.08t.397.069q.199.032.402.059q.202.027.407.049q.204.021.411.037q.206.017.414.027q.208.011.416.017q.208.005.417.005q.529 0 1.053-.035m3.636-.712q.811-.284 1.48-.657t1.161-.818m.333-.331q.413-.455.625-.948T20 11.75v-3.5m-12.75 0a4.25 1.75 0 1 0 8.5 0a4.25 1.75 0 1 0-8.5 0Zm7.5 9.75l2 2L21 15.75");
}

</style>
