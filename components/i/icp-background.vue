<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ib6sqo8yb"/><path clip-rule="evenodd" class="r7b7zvb3e"/><path clip-rule="evenodd" class="w74z2v1yc"/><path class="q0877cbkc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:icp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ib6sqo8yb {
  fill: var(--svg-color--46abe3, #46abe3);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q0877cbkc {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.896 11.932l.096.084l.98 1.248c1.152 1.076 2.832 2.4 4.36 2.4a3.65 3.65 0 0 0 3.6-2.904c-.312.564-1.4 1.448-3.344 1.428q-.15.019-.312.02c-1.252 0-2.76-1.504-3.328-2.144l.012-.016l-1.18-1.42l-1.18-1.12c-.944-.72-1.92-1.172-2.992-1.172c-1.812 0-3.268 1.44-3.56 3.16c.808-1.464 2.548-1.936 4.076-1.532c1 .172 1.868.968 2.772 1.968");
}

.r7b7zvb3e {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m12 13.232l.02-.024c1.168 1.136 2.852 2.456 4.312 2.456a3.633 3.633 0 0 0 3.668-3.6c0-1.988-1.64-3.6-3.668-3.6c-1.552 0-3.08 1.152-4.332 2.432zm4.28.976c1.248 0 2.26-.96 2.26-2.144S17.528 9.92 16.276 9.92s-2.472 1.16-3.328 2.144c.568.64 2.08 2.144 3.328 2.144z");
}

.w74z2v1yc {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m12.048 13.28l-.08-.08c-1.132 1.124-2.8 2.464-4.3 2.464A3.633 3.633 0 0 1 4 12.064c0-1.988 1.64-3.6 3.668-3.6c1.576 0 3.04 1.244 4.272 2.572l.108-.112zm-4.328.928c-1.252 0-2.264-.96-2.264-2.144S6.468 9.92 7.72 9.92s2.472 1.16 3.328 2.144c-.568.64-2.08 2.144-3.328 2.144");
}

</style>
