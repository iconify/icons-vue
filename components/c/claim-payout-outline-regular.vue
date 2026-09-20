<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="ohhz_s35v"/><path class="yb0sj-xar"/><path class="cji751bjl"/><path class="nweyncbfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:claim-payout-outline-regular" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.cji751bjl {
  d: path("M9 7.5h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nweyncbfh {
  d: path("M12.5 5 15 7.5 12.5 10");
}

.ohhz_s35v {
  d: path("M12 12v6");
}

.t9gnp4b0n {
  d: path("M3 12a9 9 0 0 1 18 0");
}

.yb0sj-xar {
  d: path("M12 18a2 2 0 0 1 -4 0");
}

</style>
