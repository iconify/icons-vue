<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="os7ac6btr"/><path class="wsqcqg43v"/><path class="jelow0iyw"/><path class="u-17h2guv"/><path class="vvjrvabrl"/><path class="g78ggbbcr"/><path class="ofu1c3b7o"/><path class="s762m2bog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-pride-16-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g78ggbbcr {
  fill: var(--svg-color--1793e8, #1793E8);
  d: path("M3 8h10v1H3z");
}

.jelow0iyw {
  fill: var(--svg-color--f36d38, #F36D38);
  d: path("M3 5h10v1H3z");
}

.ofu1c3b7o {
  fill: var(--svg-color--b73fbb, #B73FBB);
  d: path("M3 9h10v1H3z");
}

.os7ac6btr {
  fill: var(--svg-color--745125, #745125);
  d: path("M3 3h10v1H3z");
}

.s762m2bog {
  d: path("M2.5 2h11a.5.5 0 0 1 .5.5v8a.5.5 0 0 1-.5.5H3v2.5a.5.5 0 0 1-1 0v-11a.5.5 0 0 1 .5-.5zM3 3v7h10V3H3z");
  fill: var(--svg-color--212121, #212121);
}

.u-17h2guv {
  fill: var(--svg-color--ffd23e, #FFD23E);
  d: path("M3 6h10v1H3z");
}

.vvjrvabrl {
  fill: var(--svg-color--61bc51, #61BC51);
  d: path("M3 7h10v1H3z");
}

.wsqcqg43v {
  fill: var(--svg-color--e62c46, #E62C46);
  d: path("M3 4h10v1H3z");
}

</style>
