<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="lekj2ibwt"/><path class="baj885l1q"/><path class="l1w4fizaq"/><path class="uda221vxc"/><path class="hdxpysbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:folding-stool-circle" /></template>
<style>
.baj885l1q {
  d: path("M9 9a1 1 0 0 1 1 1v2.5a1 1 0 1 1-2 0V10a1 1 0 0 1 1-1m8 0a1 1 0 0 1 1 1v2.5a1 1 0 1 1-2 0V10a1 1 0 0 1 1-1");
}

.hdxpysbbn {
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.l1w4fizaq {
  d: path("M17 4a1 1 0 0 1 1 1v5a1 1 0 1 1-2 0V5a1 1 0 0 1 1-1m1.825 17.565a1 1 0 0 1-1.39.26l-9.5-6.5a1 1 0 0 1 1.13-1.65l9.5 6.5a1 1 0 0 1 .26 1.39");
}

.lekj2ibwt {
  d: path("M6.5 14A1.5 1.5 0 0 1 8 12.5h10a1.5 1.5 0 0 1 0 3H8A1.5 1.5 0 0 1 6.5 14M9 4a1 1 0 0 1 1 1v5a1 1 0 0 1-2 0V5a1 1 0 0 1 1-1");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.uda221vxc {
  d: path("M7.175 21.565a1 1 0 0 0 1.39.26l9.5-6.5a1 1 0 1 0-1.13-1.65l-9.5 6.5a1 1 0 0 0-.26 1.39M17 7H9V5h8zm0 3H9V8h8zM5 11a1 1 0 0 1 1-1h2a1 1 0 0 1 0 2H6a1 1 0 0 1-1-1m12 0a1 1 0 0 1 1-1h2a1 1 0 1 1 0 2h-2a1 1 0 0 1-1-1");
}

</style>
