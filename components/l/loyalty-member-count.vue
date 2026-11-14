<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2c4lcc9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loyalty-member-count" /></template>
<style>
.s2c4lcc9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-3 13c0-3.75 3-6.25 6.5-6.25q.415 0 .819.046M14.25 3.25q.081-.033.164-.061q.082-.029.166-.053t.17-.043t.171-.034q.086-.015.173-.025t.174-.016t.174-.006q.088-.001.175.003t.174.013t.174.022q.086.013.171.031t.17.04q.085.023.168.05t.165.058q.081.032.161.067t.157.076q.078.04.154.084q.075.044.148.092t.143.1t.138.108t.132.115t.125.121q.061.063.118.129q.058.065.112.134t.104.14t.097.146q.046.074.088.151q.042.076.08.155q.038.078.072.159t.063.163q.03.082.055.166t.045.169q.042.174.064.353q.023.178.025.358q.003.179-.014.358t-.054.355t-.093.346t-.13.335q-.075.163-.167.318q-.092.154-.2.297m-.968.854q-.625.36-1.344.422m2 4.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
