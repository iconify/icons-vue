<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="og2ph6b9i"/><path class="nppa63bea"/><path class="s1fwn9buu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-gift" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nppa63bea {
  d: path("M12.8 21H6.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-6q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026t.172-.008h9.5q.276 0 .539.085q.264.085.487.248M11 7.5V21m0-13.5c-2.5-4.5-5.5-3-3.5 0m3.5 0c2.5-4.5 5.5-3 3.5 0m1 8.25a3 1.25 0 1 0 6 0a3 1.25 0 1 0-6 0");
}

.og2ph6b9i {
  d: path("M4.75 7.5h12.5A1.75 1.75 0 0 1 19 9.25v.5a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 9.75v-.5A1.75 1.75 0 0 1 4.75 7.5");
}

.s1fwn9buu {
  d: path("M15.5 15.75V20a3 1.25 0 0 0 6 0v-4.25");
}

</style>
