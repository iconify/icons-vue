<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGnYv1vdJA)" class="r4i437pya"/><path class="bqq-zfbcg"/></g><defs><linearGradient id="SVGnYv1vdJA" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="pzgty9nbc"/><stop offset=".49" class="uwbv3v-lj"/><stop offset="1" class="r57tztb-g"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ilv-background" /></template>
<style>
.bqq-zfbcg {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.346 10.205c-.056-.06-.087-.116-.026-.194a8.56 8.56 0 0 0 1.652-3.56c.108-.522.147-1.054.19-1.582c.021-.29.043-.58.078-.869h.03v6.616c-.004.835-.017 3.157 0 4.515l.013.778l.009.532c.004.333.095.64.32.9q.118.135.216.285c.07.1.07.195-.043.272a65 65 0 0 0-2.604 1.955l-.073.03c.156-.341.264-.662.376-.977v-.009a9.9 9.9 0 0 0 .489-3.304v-1.699l.004-1.743c-.009-.661-.147-1.448-.631-1.946m5.384 3.105V7.788c.008-.653.004-1.323 0-1.99V4h.038c.1.964.208 1.929.424 2.876a8.3 8.3 0 0 0 1.358 2.962c.182.255.182.26 0 .493l-.009.008c-.389.498-.51 1.194-.51 1.812l-.004 3.438c0 1.003.212 1.946.432 2.92l.087.388c.065.29.216.692.346.982c-.06.004-.091-.022-.121-.052l-.018-.013a60 60 0 0 0-2.525-1.911c-.121-.082-.139-.173-.06-.286a1 1 0 0 1 .09-.12a1.75 1.75 0 0 0 .472-1.298v-2.897zM8.973 20v-.022c.458-.337.92-.657 1.383-.977c.494-.333.982-.67 1.462-1.03a.33.33 0 0 1 .182-.077c.06 0 .117.03.181.078c.48.359.969.692 1.458 1.03c.467.319.93.64 1.388.976V20L15 19.987l-.052-.026a6.8 6.8 0 0 0-2.95-.804c-.963 0-2.11.359-2.948.804l-.048.026z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.pzgty9nbc {
  stop-color: var(--svg-color--5d2872, #5d2872);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.r57tztb-g {
  stop-color: var(--svg-color--232651, #232651);
}

.uwbv3v-lj {
  stop-color: var(--svg-color--3a2f71, #3a2f71);
}

</style>
