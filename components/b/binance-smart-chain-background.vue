<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xcdttwxtv"/><path class="tdge565lk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:binance-smart-chain-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tdge565lk {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.635 6.449L12 4l4.364 2.449l-1.6.907L12 5.809L9.24 7.356zm8.73 3.093l-1.6-.906L12 10.182L9.24 8.636l-1.605.906v1.81l2.756 1.546v3.089l1.609.906l1.604-.906v-3.09l2.76-1.546zm0 4.903V12.63l-1.6.907v1.809zm1.141.64l-2.76 1.542v1.813l4.365-2.453v-4.898l-1.605.902zm-1.604-7.09l1.6.907v1.81l1.609-.903V7.996l-1.605-.907L15.902 8zm-5.511 9.29v1.808L12 20l1.604-.907V17.29l-1.604.9l-1.605-.907zM7.635 14.44l1.6.907v-1.81l-1.6-.906v1.813zm2.756-6.444L12 8.902l1.604-.906L12 7.089L10.395 8zm-3.898.906l1.605-.906l-1.6-.907L4.888 8v1.813l1.605.903zm0 3.09l-1.604-.903v4.898l4.364 2.453v-1.818L6.498 15.08v-3.093z");
}

.xcdttwxtv {
  fill: var(--svg-color--f0b90b, #f0b90b);
  d: path("M24 0H0v24h24z");
}

</style>
