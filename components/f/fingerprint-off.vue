<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o2gocx2nn"/><path class="p5vmqpb5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fingerprint-off" /></template>
<style>
.o2gocx2nn {
  d: path("M4 16v-3.5q0-.957.226-1.886q.225-.93.664-1.78m4.178-3.777q.7-.276 1.44-.417q.739-.14 1.492-.14q.196 0 .393.01q.196.009.391.029q.196.019.39.048q.194.028.387.067q.192.038.383.086q.19.047.378.104t.373.124t.366.141t.359.159t.351.177t.342.193t.332.21t.321.226t.309.242t.297.256q.146.132.285.271t.271.285q.131.145.256.297t.242.309q.117.158.226.321q.109.164.21.332q.101.169.193.342q.093.173.177.351q.084.177.159.359q.075.181.141.366q.067.185.124.373t.104.378t.086.383t.067.387t.048.39t.029.391q.01.197.01.393v3");
}

.p5vmqpb5p {
  d: path("M7.5 19.5v-7q0-.482.102-.954m4.316-3.545L12 8q.11 0 .221.005q.11.006.22.017q.11.01.219.027q.11.016.218.037q.108.022.215.049q.108.027.213.059q.106.032.21.069t.206.08t.202.089t.197.099t.192.109t.187.118t.181.128q.088.065.174.135t.167.145q.082.074.16.152t.152.16t.145.167q.07.086.135.174q.066.089.128.181q.061.092.118.187q.057.094.109.192q.052.097.099.197t.089.202t.08.206t.069.21q.032.105.059.213q.027.107.049.215q.021.108.037.218q.017.109.027.219q.011.11.017.22q.005.111.005.221v.023M12 21v-5.1M3.5 3.5l17 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
