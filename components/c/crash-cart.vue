<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wjp-w0plf"/><path class="vslnyjjat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crash-cart" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vslnyjjat {
  d: path("m18.5 16l-1.25 2h1.5l-1.25 2");
}

.wjp-w0plf {
  d: path("M11.7 17H3V5h12.5v7M3 2.5V5m0-2.5h3M3.75 19.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm8.065-1.288q-.134.123-.239.271q-.106.148-.179.314q-.072.166-.11.344q-.037.177-.037.359q0 .086.008.172t.026.169q.016.085.041.167t.058.162t.074.155t.088.147q.048.072.102.138q.055.067.116.127q.06.061.127.116q.066.054.138.102q.071.048.147.088q.076.041.155.074q.08.033.162.058t.167.041t.169.026Q12.914 21 13 21q.169 0 .335-.032M3 11h12.5m-8-3H11m-3.5 6H11m7 7.25s-3.5-2.25-3.5-4.5c0-1 .75-2 1.75-2c.75 0 1.5.5 1.75 1c.25-.5 1-1 1.75-1c1 0 1.75 1 1.75 2c0 2.25-3.5 4.5-3.5 4.5Z");
}

</style>
