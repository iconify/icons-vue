<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d0rewwdky"/><path class="sg0xgbc0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:house-clock" /></template>
<style>
.d0rewwdky {
  d: path("M12.244 19.5H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-6.46q0-.186.039-.368t.116-.352t.187-.319t.25-.273l6.75-5.956q.059-.052.123-.099t.132-.088t.139-.075t.145-.063t.15-.049t.154-.035t.157-.022t.158-.007t.158.007t.157.022t.154.035t.15.049t.145.063t.139.075t.132.088t.123.099l6.75 5.956q.14.123.25.273q.111.15.187.319q.077.17.116.352t.039.368v.441");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sg0xgbc0w {
  d: path("M16.75 15.5h2.5A1.75 1.75 0 0 1 21 17.25v2.25a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.5v-2.25a1.75 1.75 0 0 1 1.75-1.75M15 17.75h6m-4.25-3.25V16m2.5-1.5V16");
}

</style>
