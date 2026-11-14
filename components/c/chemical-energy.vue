<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="obok8umwv"/><path class="kr8ra2byu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chemical-energy" /></template>
<style>
.kr8ra2byu {
  d: path("M6.5 16a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5-3.5h.01m7.74 1L15 18.75h3L16.75 22L21 16.5h-3Z");
}

.obok8umwv {
  d: path("M7.5 3h5m-4 0v5.5q-.192.045-.38.102q-.189.057-.374.126q-.184.068-.365.147q-.18.08-.355.17t-.345.191q-.169.1-.332.211t-.319.231t-.305.25q-.148.129-.288.268q-.141.138-.272.284q-.132.147-.254.301q-.123.155-.236.316t-.216.329t-.196.342t-.174.353t-.153.363t-.131.372t-.107.378q-.049.191-.085.385t-.062.389q-.024.195-.037.392t-.014.394t.01.393t.034.393q.023.195.058.389q.034.194.081.386q.046.191.104.379q.058.189.127.373q.069.185.149.365q.081.18.172.354q.091.175.192.344t.213.331q.2.292.431.561t.49.51q.258.242.542.455q.283.212.588.392t.628.327q.322.146.659.256t.683.183t.699.108m6.841-8.419q-.063-.2-.139-.396t-.164-.386q-.089-.191-.189-.375t-.212-.362q-.112-.177-.236-.347t-.257-.332q-.134-.162-.278-.314q-.144-.153-.298-.296t-.316-.276q-.163-.132-.334-.254q-.17-.123-.349-.233t-.363-.21q-.185-.099-.377-.186q-.191-.087-.387-.161t-.397-.136t-.405-.11V3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
