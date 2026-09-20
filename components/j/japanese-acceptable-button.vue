<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGIV14UcJl" class="o7htj-bqt"/></defs><circle class="zyw7z0bdq"/><circle class="jw7_rhhqg"/><use href="#SVGIV14UcJl" class="e0ty9gbgt"/><path class="e9ly9kbcx"/><use href="#SVGIV14UcJl" class="pfsdhbbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:japanese-acceptable-button" /></template>
<style>
.e0ty9gbgt {
  opacity: var(--svg-opacity--0-65, 0.65);
}

.e9ly9kbcx {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M74.4 106.1c-1.6 0-2.9-.3-4.1-.8c-1.4-.7-2.3-1.6-2.8-2.8c-.7-1.9-.4-3.3.8-4.1c1-.8 2.7-1.1 5.1-1h8.3q1.5-.15 2.1-.6c.4-.3.5-1 .5-1.9V38.1H28.5c-2.8 0-4.1-1.4-4.1-4.2s1.4-4.1 4.1-4.1h71c2.8 0 4.1 1.4 4.1 4.1c0 2.8-1.4 4.2-4.1 4.2H93V95q0 4.2-1.2 6.3c-.8 1.5-2.1 2.5-4 3.1c-2.5 1-6.9 1.6-13.4 1.7M39 83.8c-1.7 0-3.1-.5-4.2-1.6s-1.6-2.5-1.6-4.2V55.8c0-1.7.5-3.1 1.6-4.2S37.3 50 39 50h25c1.7 0 3.1.5 4.2 1.6s1.6 2.5 1.6 4.2v22.1c0 1.7-.5 3.1-1.6 4.2s-2.5 1.6-4.2 1.6H39zm4.4-8h16.1c1.4 0 2.2-.7 2.2-2.2V60c0-1.4-.7-2.2-2.2-2.2H43.4c-1.4 0-2.2.7-2.2 2.2v13.7c0 1.4.8 2.1 2.2 2.1");
}

.jw7_rhhqg {
  cx: 60px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--ff9800, #ff9800);
}

.o7htj-bqt {
  fill: var(--svg-color--ffbd52, #ffbd52);
  d: path("M23.9 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5c-9.4 3.1-17.5 9.2-23 17.4c-2 3-5 11.3-8.7 9.2c-3.9-2.3-3.1-9.5 2.6-18.3");
}

.pfsdhbbki {
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zyw7z0bdq {
  cx: 63.9px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--f77e00, #f77e00);
}

</style>
