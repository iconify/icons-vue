<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rzz7i9b1f"/><path class="g7vky-tem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-equipment" /></template>
<style>
.g7vky-tem {
  d: path("M17 3h2a3 3 0 0 1 0 6h-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rzz7i9b1f {
  d: path("M6.5 6v11.9m-.3 1.6H2.5m6-4.125V13.75q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147q.048-.072.102-.138q.055-.067.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026t.172-.008h7.5q.086 0 .172.008t.169.026q.085.016.167.041t.162.058t.155.074t.147.088q.072.048.138.102q.067.055.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167t.026.169q.008.086.008.172v1.625M10 12V8h1.5m3.789 3.578L15.5 12m-9 3h2m.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M14 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
