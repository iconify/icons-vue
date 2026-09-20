<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="i-nikabdx"/><path class="w0hvtcc_r"/><path class="npzn5xbkm"/><path class="htd-jqwaw"/><path class="hdxpysbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:clipboard-check-circled-circle" /></template>
<style>
.hdxpysbbn {
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.htd-jqwaw {
  d: path("M18.87 14.72a1 1 0 0 1 .156 1.405l-1.65 2.063a1.5 1.5 0 0 1-2.233.124l-1.104-1.105a1 1 0 0 1 1.414-1.414l.71.71l1.302-1.628a1 1 0 0 1 1.405-.156");
}

.i-nikabdx {
  d: path("M8.68 5.5a1 1 0 0 1 1-1h6.643a1 1 0 0 1 1 1v3.875a1 1 0 0 1-1 1H9.68a1 1 0 0 1-1-1zm2 1v1.875h4.643V6.5z");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.npzn5xbkm {
  d: path("M16.5 20a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7m0 2a5.5 5.5 0 1 0 0-11a5.5 5.5 0 0 0 0 11");
}

.w0hvtcc_r {
  d: path("M8 19V8h1V6H7a1 1 0 0 0-1 1v13a1 1 0 0 0 1 1h6.337a5.5 5.5 0 0 1-1.737-2zm10-7.793c.742.21 1.421.572 2 1.05V7a1 1 0 0 0-1-1h-2v2h1z");
}

</style>
