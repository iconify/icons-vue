<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ygohncc4c"/><path clip-rule="evenodd" class="ud503rbeq"/><path clip-rule="evenodd" class="uhobuz89t"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gtc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ud503rbeq {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M16.65 12.672a3.64 3.64 0 0 0-1.345-2.829l.89-1.095a5.05 5.05 0 0 1 1.867 3.924a5.05 5.05 0 0 1-1.867 3.924l-.89-1.095a3.64 3.64 0 0 0 1.346-2.83");
}

.uhobuz89t {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M9.587 4.47a.47.47 0 1 1 .941 0v1.812q.689-.242 1.412-.339V4.471a.47.47 0 1 1 .941 0v1.41a7.03 7.03 0 0 1 5.274 2.368l.024.028l-3.736 3.308a2.11 2.11 0 0 1-.138 2.437l3.752 2.905V20H12.88A7.06 7.06 0 0 1 9.587 6.695zm3.702 10.254a2.116 2.116 0 0 1-2.44-3.136a2.12 2.12 0 0 1 2.712-.793l2.872-2.543a5.85 5.85 0 0 0-3.552-1.194c-.837 0-1.632.174-2.352.489v2.1a.47.47 0 1 1-.941 0V8.065a5.88 5.88 0 0 0-2.59 4.876a5.883 5.883 0 0 0 5.882 5.883l.1-.001h3.9v-1.32zm.298-2.019a.94.94 0 1 1-1.882 0a.94.94 0 0 1 1.882 0");
}

.ygohncc4c {
  fill: var(--svg-color--0e0333, #0e0333);
  d: path("M24 0H0v24h24z");
}

</style>
