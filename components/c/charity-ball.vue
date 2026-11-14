<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w2t817-bq"/><path class="k309_gbyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charity-ball" /></template>
<style>
.k309_gbyt {
  d: path("M5.5 9.75a2 1.5 0 1 0 4 0a2 1.5 0 1 0-4 0Zm11.824-1.367q-.393-.133-.824-.133q-.098 0-.196.007t-.194.022q-.097.014-.191.036t-.184.049t-.178.063q-.086.035-.168.076t-.158.087q-.076.047-.145.099q-.07.052-.132.109t-.117.119t-.101.126t-.084.133t-.066.139t-.048.142q-.019.073-.028.146t-.01.147q0 .125.028.249t.082.242t.135.229t.184.208q.103.099.227.183t.265.152t.294.117t.317.078M17.75 14l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w2t817-bq {
  d: path("M9.204 15.297A3.6 3.6 0 0 1 8 15.5c-3 0-5.5-4-5.5-10c4-1 7 0 9.5 1.5c2.5-1.5 5.5-2.5 9.5-1.5c0 2.8-.544 5.164-1.43 6.889m-7.266 1.464c-.28-.295-.542-.591-.804-.853c-.347.347-.695.755-1.084 1.139");
}

</style>
