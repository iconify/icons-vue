<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGmzq9bcpY" class="g4u6vkyhs"/></defs><circle class="nnkmwgb1m"/><circle class="ebdow9b1a"/><use href="#SVGmzq9bcpY" class="e0ty9gbgt"/><path class="jzi5tdbml"/><use href="#SVGmzq9bcpY" class="pfsdhbbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:circled-m" /></template>
<style>
.e0ty9gbgt {
  opacity: var(--svg-opacity--0-65, 0.65);
}

.ebdow9b1a {
  cx: 60.03px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--2262dd, #2262dd);
}

.g4u6vkyhs {
  fill: var(--svg-color--68abe6, #68abe6);
  d: path("M23.93 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5a44.64 44.64 0 0 0-23 17.4c-2 3-5 11.3-8.7 9.2c-3.9-2.3-3.1-9.5 2.6-18.3");
}

.jzi5tdbml {
  fill: var(--svg-color--fbf9f9, #fbf9f9);
  d: path("M29.6 34.15h15.01L61 77.55h.69l16.39-43.39h15.1v61.77H81.61V65.47l.69-10.26h-.69l-15.7 40.72h-9.06L41.07 55.2h-.69l.69 10.26v30.45H29.6z");
}

.nnkmwgb1m {
  cx: 63.93px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--194fa5, #194fa5);
}

.pfsdhbbki {
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
