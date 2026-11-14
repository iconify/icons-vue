<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dccbznxit"/><path class="hm0w54bzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:landlord-dispute" /></template>
<style>
.dccbznxit {
  d: path("M11.854 21H4.75q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q3 19.336 3 19.25v-7.93q0-.193.042-.38q.042-.188.123-.363q.082-.174.199-.326t.266-.276l7.25-6.041q.117-.097.249-.173t.275-.128t.294-.078t.302-.026t.302.026t.294.078t.275.128t.249.173l7.25 6.041q.148.123.266.276q.117.152.199.326q.081.175.123.363q.042.187.042.38v.601");
}

.hm0w54bzg {
  d: path("M7.5 21v-6H12v3.2m2.5 1.55a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3-1.25l3.75-3.75m-1.5 1.5l1.5 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
