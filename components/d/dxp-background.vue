<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="shr706bbd"/><path class="aw0dysbmp"/><path class="qexmd1j_a"/><path class="bma1ubcrj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dxp-background" /></template>
<style>
.aw0dysbmp {
  fill: var(--svg-color--2b56fe, #2b56fe);
  d: path("M11.844 19.996a2.17 2.17 0 0 1-1.386-.636l-4.813-4.818h12.72l-4.823 4.818c-.37.374-.862.601-1.386.64h-.312z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bma1ubcrj {
  fill: var(--svg-color--b1e1ff, #b1e1ff);
  d: path("m18.298 9.396l1.067 1.066q.234.236.382.516a2.2 2.2 0 0 1-.733-.511c-.347-.369-.783-.711-1.29-.711c-.51 0-.942.342-1.288.71a2.177 2.177 0 0 1-3.174 0c-.35-.368-.782-.71-1.288-.71c-.511 0-.947.342-1.294.71a2.176 2.176 0 0 1-3.173 0c-.347-.368-.782-.71-1.289-.71c-.511 0-.942.342-1.289.71a2.3 2.3 0 0 1-.658.476a2.3 2.3 0 0 1 .37-.484l1.062-1.062l4.755-4.756a2.176 2.176 0 0 1 3.084 0l2.53 2.525z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qexmd1j_a {
  fill: var(--svg-color--3b82ff, #3b82ff);
  d: path("M4.195 12.903c.109.238.26.455.445.64l2.622 2.622q.125.114.244.24a2.18 2.18 0 0 0 3.174 0c.346-.373.782-.711 1.289-.711s.942.338 1.288.711a2.18 2.18 0 0 0 3.174 0c.155-.164.329-.324.515-.449l2.413-2.413c.2-.2.356-.427.458-.671q-.466.181-.8.542c-.355.369-.786.707-1.293.707c-.511 0-.942-.338-1.289-.712a2.176 2.176 0 0 0-3.173 0c-.351.374-.787.712-1.289.712c-.511 0-.947-.338-1.293-.712a2.175 2.175 0 0 0-3.174 0c-.35.374-.782.712-1.288.712c-.512 0-.943-.338-1.29-.712a2.2 2.2 0 0 0-.733-.506");
}

.shr706bbd {
  fill: var(--svg-color--5fadff, #5fadff);
  d: path("M4.64 10.458a2.18 2.18 0 0 0 0 3.084l1 1h12.72l1-1a2.18 2.18 0 0 0 0-3.084l-1.062-1.063H5.702l-1.066 1.067z");
}

</style>
