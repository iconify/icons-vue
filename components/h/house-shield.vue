<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cafxt_brl"/><path class="rd2demb6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:house-shield" /></template>
<style>
.cafxt_brl {
  d: path("M12.744 20.5H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-7.46q0-.186.039-.368t.116-.352t.187-.319t.25-.273l6.75-5.956q.059-.052.123-.099t.132-.088t.139-.075t.145-.063t.15-.049t.154-.035t.157-.022t.158-.007t.158.007t.157.022t.154.035t.15.049t.145.063t.139.075t.132.088t.123.099l6.75 5.956q.14.123.25.273q.111.15.187.319q.077.17.116.352t.039.368v.241");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rd2demb6e {
  d: path("M8 20.5v-5h4v5m6.25-6.5l3.25 1.25V18c0 1.9-1.4 3.1-3.25 4c-1.85-.9-3.25-2.1-3.25-4v-2.75Z");
}

</style>
