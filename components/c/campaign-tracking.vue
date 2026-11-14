<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rkdzv4b1g"/><path class="chdpn154b"/><path class="st8bpl8_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campaign-tracking" /></template>
<style>
.chdpn154b {
  d: path("m4.5 11.5l1.25 5h2.5l-.5-4.75m7 2.75v6.75h6.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rkdzv4b1g {
  d: path("m11.999 13.852l-4.645-2.185Q7 11.5 6.609 11.5H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q2.5 9.836 2.5 9.75v-1q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026Q4.164 7 4.25 7h2.315Q7 7 7.384 6.797l5.547-2.937q.05-.026.101-.049t.104-.043t.107-.036t.108-.029t.111-.023q.055-.009.111-.015q.056-.005.113-.007q.056-.002.112-.001q.056.002.112.007q.057.005.112.014q.056.009.111.021t.109.028t.107.035t.104.042t.102.048t.098.055t.094.061q.047.033.091.068t.085.072t.081.078t.076.084t.071.087t.064.093t.059.096q.027.049.052.099t.045.103q.022.052.039.106q.018.053.033.108q.014.054.025.109l.018.112q.007.055.01.112q.004.056.004.112v6.42");
}

.st8bpl8_q {
  d: path("m16.75 19l1.5-2.25L19.5 18l2-2.75");
}

</style>
