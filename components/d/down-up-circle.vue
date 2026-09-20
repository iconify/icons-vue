<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="jzvsr_xci"/><path class="nm0-ihg2c"/><path class="nm27pnbqj"/><path class="f-u6zfboc"/><path class="s6joy3b1i"/><path class="hdxpysbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:down-up-circle" /></template>
<style>
.f-u6zfboc {
  d: path("M5.293 15.293a1 1 0 0 1 1.414 0l3 3a1 1 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414");
}

.hdxpysbbn {
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.jzvsr_xci {
  d: path("M13.293 10.707a1 1 0 0 1 0-1.414l3-3a1 1 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.nm0-ihg2c {
  d: path("M20.707 10.707a1 1 0 0 1-1.414 0l-3-3a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414");
}

.nm27pnbqj {
  d: path("M17 8a1 1 0 0 1 1 1v8a1 1 0 1 1-2 0V9a1 1 0 0 1 1-1m-4.293 7.293a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0");
}

.s6joy3b1i {
  d: path("M9 18a1 1 0 0 1-1-1V9a1 1 0 1 1 2 0v8a1 1 0 0 1-1 1");
}

</style>
