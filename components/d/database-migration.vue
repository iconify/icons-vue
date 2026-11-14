<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jbhy6j9sj"/><path class="ypdpddche"/><path class="hjeixgbjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-migration" /></template>
<style>
.hjeixgbjr {
  d: path("M2.5 12A5.25 2.75 0 0 0 13 12m2.75 4.25h5.75m-2-2l2 2m0 3.5h-5.75m2 2l-2-2");
}

.jbhy6j9sj {
  d: path("M2.5 5.25a5.25 2.75 0 1 0 10.5 0a5.25 2.75 0 1 0-10.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ypdpddche {
  d: path("M2.5 5.25v13.5q0 .068.006.135q.007.067.019.135q.013.067.032.134q.019.066.044.132q.025.067.056.132q.032.066.069.13q.037.065.081.128q.043.064.093.126q.049.063.104.124t.116.12t.127.118t.138.114t.148.11t.159.107q.081.052.168.102t.178.098t.186.093q.096.045.195.088q.1.043.204.083t.21.078q.107.037.218.072t.224.066q.114.032.23.061q.117.029.236.055t.24.048q.122.023.245.043t.248.036t.252.029t.254.023t.255.017l.257.01q.129.003.258.003q.337 0 .671-.023q.335-.022.661-.067t.639-.111t.606-.153t.564-.192q.27-.106.512-.229t.452-.261t.385-.289m.76-6.77V5.25");
}

</style>
