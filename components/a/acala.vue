<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGKBumycTO)" clip-rule="evenodd" class="o46_gabxe"/><defs><linearGradient id="SVGKBumycTO" x1="19.99" x2="6.71" y1="21" y2="4.598" gradientUnits="userSpaceOnUse"><stop class="mamuo5b0r"/><stop offset=".524" class="vtoc0-r2p"/><stop offset="1" class="v28ua0nqc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:acala" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mamuo5b0r {
  stop-color: var(--svg-color--5a81ff, #5a81ff);
}

.o46_gabxe {
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m.037-.845a8.155 8.155 0 1 0 0-16.31a8.155 8.155 0 0 0 0 16.31M12 19.531a7.53 7.53 0 1 0 0-15.062a7.53 7.53 0 0 0 0 15.062m.018-.919a6.63 6.63 0 1 0 0-13.261a6.63 6.63 0 0 0 0 13.261m-.374-11.988l4.8 8.328l.515-.893l-4.285-7.435zm-4.603 7.42l4.108-7.128l.009.015l.008-.014l4.869 8.447h-1.03l-1.23-2.134a5.9 5.9 0 0 0-1.771-.272q-.478 0-.93.066l.592-1.027a7 7 0 0 1 1.445.081l-1.954-3.39l-3.601 6.249zm2.793-.108l1.846-3.203l-.515-.893l-3.184 5.524h1.03l.01-.017c.883-.532 1.896-.8 3.002-.8a5.9 5.9 0 0 1 2.011.353l-.69-1.195a6.9 6.9 0 0 0-3.51.23");
}

.v28ua0nqc {
  stop-color: var(--svg-color--ff4c3b, #ff4c3b);
}

.vtoc0-r2p {
  stop-color: var(--svg-color--e40c5b, #e40c5b);
}

</style>
