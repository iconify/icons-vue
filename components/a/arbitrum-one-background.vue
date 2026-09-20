<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y8anb9vhj"/><path class="av041wbjf"/><path class="jltgle4qo"/><path class="mhsmzybsv"/><path class="vha9-b_ol"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arbitrum-one-background" /></template>
<style>
.av041wbjf {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.203 13.216l-.787 2.124a.27.27 0 0 0 0 .183l1.354 3.655l1.565-.89l-1.879-5.072c-.042-.117-.21-.117-.253 0m1.577-3.573a.135.135 0 0 0-.253 0l-.787 2.124a.27.27 0 0 0 0 .183l2.217 5.985l1.565-.89z");
}

.ft5dv1b6b {
  fill: none;
}

.jltgle4qo {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.999 4.991a.24.24 0 0 1 .111.03l5.969 3.393a.22.22 0 0 1 .112.19v6.787a.22.22 0 0 1-.112.19l-5.969 3.395a.2.2 0 0 1-.111.029a.24.24 0 0 1-.113-.03l-5.968-3.39a.22.22 0 0 1-.112-.19v-6.79a.22.22 0 0 1 .112-.19l5.969-3.393a.23.23 0 0 1 .111-.03m0-.991c-.213 0-.426.054-.616.163L5.416 7.556a1.21 1.21 0 0 0-.616 1.05v6.787c0 .433.234.834.616 1.05l5.968 3.394a1.25 1.25 0 0 0 1.232 0l5.968-3.394a1.21 1.21 0 0 0 .616-1.05V8.606a1.21 1.21 0 0 0-.616-1.05l-5.97-3.393A1.24 1.24 0 0 0 11.998 4");
}

.mhsmzybsv {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.052 17.943l.55-1.482l1.105.905l-1.034.93zm3.445-9.823H9.984a.27.27 0 0 0-.254.175l-3.243 8.757l1.565.89L11.623 8.3a.132.132 0 0 0-.127-.179");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vha9-b_ol {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.144 8.12h-1.513a.27.27 0 0 0-.253.175l-3.704 10l1.565.89l4.032-10.886a.133.133 0 0 0-.127-.179");
}

.y8anb9vhj {
  fill: var(--svg-color--213147, #213147);
  d: path("M24 0H0v24h24z");
}

</style>
