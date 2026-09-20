<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bxg9y62pw"/><circle class="qxluyohyz"/><circle class="dbt568qii"/><circle class="fpi3zj0ul"/><path class="x-bkihbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:ghost" /></template>
<style>
.bxg9y62pw {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M36 11a2 2 0 0 0-4 0s-.011 3.285-3 3.894V12c0-6.075-4.925-11-11-11S7 5.925 7 12v3.237C1.778 16.806 0 23.231 0 27a2 2 0 0 0 4 0s.002-3.54 3.336-3.958C7.838 27.883 8.954 33 11 33h1c4 0 3 2 7 2s3-2 6-2s2.395 2 6 2a3 3 0 0 0 3-3c0-.675-2.274-4.994-3.755-9.268C35.981 21.348 36 14.58 36 11");
}

.dbt568qii {
  cx: 23px;
  cy: 12px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.fpi3zj0ul {
  cx: 23px;
  cy: 13px;
  r: 2px;
  fill: var(--svg-color--9aaab4, #9aaab4);
}

.qxluyohyz {
  cx: 13px;
  cy: 12px;
  r: 2px;
  fill: var(--svg-color--292f33, #292f33);
}

.x-bkihbvf {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M22.192 19.491c2.65 1.987 3.591 5.211 2.1 7.199s-4.849 1.988-7.5 0s-3.591-5.211-2.1-7.199c1.492-1.989 4.849-1.988 7.5 0");
}

</style>
