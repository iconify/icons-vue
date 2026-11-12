<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g8_7xqb1r"/><path class="igjle7krr"/><path class="bdu_37bbc"/><path class="v059u6b0e"/><path class="nle0ke1sz"/><path class="ycdfr27mi"/><path class="jwfrwlbnf"/><path class="vvr39u97h"/><path class="i6pq2yebs"/><path class="kui2pkyus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ferris-wheel-broken" /></template>
<style>
.bdu_37bbc {
  d: path("M20.5 16C20.5 16.5523 20.0523 17 19.5 17C18.9477 17 18.5 16.5523 18.5 16C18.5 15.4477 18.9477 15 19.5 15C20.0523 15 20.5 15.4477 20.5 16Z");
}

.g8_7xqb1r {
  d: path("M14 11C14 12.1046 13.1046 13 12 13C10.8954 13 10 12.1046 10 11C10 9.89543 10.8954 9 12 9");
}

.i6pq2yebs {
  d: path("M10.5 13L5.5 22");
}

.igjle7krr {
  d: path("M20.5 7.5C20.5 8.05228 20.0523 8.5 19.5 8.5C18.9477 8.5 18.5 8.05228 18.5 7.5C18.5 6.94772 18.9477 6.5 19.5 6.5C20.0523 6.5 20.5 6.94772 20.5 7.5Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwfrwlbnf {
  d: path("M12 18.5C12.5523 18.5 13 18.9477 13 19.5C13 20.0523 12.5523 20.5 12 20.5C11.4477 20.5 11 20.0523 11 19.5C11 18.9477 11.4477 18.5 12 18.5Z");
}

.kui2pkyus {
  d: path("M4.20557 9.03117V13.9688C4.20557 15.0668 4.80539 16.0771 5.76937 16.6027L10.5636 19.2169C11.4588 19.705 12.5407 19.705 13.436 19.2169L18.2302 16.6027C19.1942 16.0771 19.794 15.0668 19.794 13.9688V9.03117C19.794 7.93319 19.1942 6.92292 18.2302 6.39728L13.436 3.78311C12.5407 3.29495 11.4588 3.29495 10.5636 3.78311L5.76937 6.39728C4.80539 6.92292 4.20557 7.93318 4.20557 9.03117Z");
}

.nle0ke1sz {
  d: path("M5.5 16C5.5 16.5523 5.05228 17 4.5 17C3.94772 17 3.5 16.5523 3.5 16C3.5 15.4477 3.94772 15 4.5 15C5.05228 15 5.5 15.4477 5.5 16Z");
}

.v059u6b0e {
  d: path("M5.5 7.5C5.5 8.05228 5.05228 8.5 4.5 8.5C3.94772 8.5 3.5 8.05228 3.5 7.5C3.5 6.94772 3.94772 6.5 4.5 6.5C5.05228 6.5 5.5 6.94772 5.5 7.5Z");
}

.vvr39u97h {
  d: path("M15.1665 16L18.4998 22");
}

.ycdfr27mi {
  d: path("M12 2.5C12.5523 2.5 13 2.94772 13 3.5C13 4.05228 12.5523 4.5 12 4.5C11.4477 4.5 11 4.05228 11 3.5C11 2.94772 11.4477 2.5 12 2.5Z");
}

</style>
