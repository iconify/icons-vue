<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="nbpio-bzr"/><path class="b--o8ebpv"/><path class="n7ljaohhg"/><path class="j8qsuojrw"/><path class="ys05igozt"/><path class="s0z06gbow"/><path class="gpep0wbxi"/><path class="gkc_2sfvl"/><path class="zr85wkbnv"/><path class="u_dvmqmbt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kai-background" /></template>
<style>
.b--o8ebpv {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.89 10.125l-2.223-5.36l3.556 1.804z");
}

.ft5dv1b6b {
  fill: none;
}

.gkc_2sfvl {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.112 14.124L10.668 11.9l6 2.223zM6.667 5.236L4 8.569l2.667 6.223l4.667 4.444z");
}

.gpep0wbxi {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.11 18.79v-4.666h3.556z");
}

.j8qsuojrw {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.89 7.014l-2.223-2.25l3.556 1.805zM20 9.236h-3.778L18 12.347zm-3.778 0l-3.333 1.333l5.11 1.778z");
}

.n7ljaohhg {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.889 10.125V7.012l1.333-.444z");
}

.nbpio-bzr {
  fill: var(--svg-color--797cb3, #797cb3);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s0z06gbow {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.406 6.125l1.817 3.11l2-3.777zM13.112 18.79l-2.444-6.889l6 2.223z");
}

.u_dvmqmbt {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.667 10.347L4 8.569l2.667 6.222l2.222-2.889z");
}

.ys05igozt {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.406 6.125l-1.517 4.445l3.333-1.334zm3.816-.667l-2 3.778H20z");
}

.zr85wkbnv {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.889 11.901l-2.222 2.89l4.666 4.444z");
}

</style>
