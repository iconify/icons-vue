<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwxgv2bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:change-failure-rate" /></template>
<style>
.kwxgv2bit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 3L5 18M3.5 6.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm14.608 5.484q-.194-.231-.433-.415t-.512-.311t-.567-.193q-.295-.065-.596-.065q-.135 0-.27.013q-.134.013-.267.04q-.132.026-.261.065q-.13.04-.254.091q-.125.052-.244.116q-.119.063-.232.138q-.112.076-.217.161q-.104.086-.2.181q-.095.096-.181.2t-.161.217t-.138.232q-.064.119-.116.244q-.051.124-.091.254q-.039.129-.065.262q-.027.132-.04.266q-.013.135-.013.27q0 .11.009.221q.009.11.026.219t.044.216t.062.212t.078.207t.094.199q.051.098.11.191q.059.094.125.182q.066.089.139.172t.153.159q.079.077.165.147q.085.07.176.133t.186.119t.195.103t.203.087t.209.071M18 14.5V18m0 3h.01");
}

</style>
