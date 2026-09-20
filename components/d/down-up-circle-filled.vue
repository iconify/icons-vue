<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGOsTmQcIH"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="jzvsr_xci"/><path class="nm0-ihg2c"/><path class="nm27pnbqj"/><path class="f-u6zfboc"/><path class="s6joy3b1i"/></g></mask></defs><circle mask="url(#SVGOsTmQcIH)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:down-up-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.f-u6zfboc {
  d: path("M5.293 15.293a1 1 0 0 1 1.414 0l3 3a1 1 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414");
}

.ft5dv1b6b {
  fill: none;
}

.jzvsr_xci {
  d: path("M13.293 10.707a1 1 0 0 1 0-1.414l3-3a1 1 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
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
