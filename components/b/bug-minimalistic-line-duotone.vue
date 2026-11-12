<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l7sg0pb6g"/><path class="xzpga8tov"/><path class="wdgiifbhr"/><path class="uh-kdpqbj"/><path class="pb1o_xtkh"/><path class="ip6dy4b-s"/><path class="ltrgokn6u"/><path class="xuz371e7m"/><path class="rf84fqwne"/><path class="gde9kxtyo"/><path class="a5qj-rbqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bug-minimalistic-line-duotone" /></template>
<style>
.a5qj-rbqa {
  d: path("M10.5 15.5H13.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gde9kxtyo {
  d: path("M10.5 10.5H13.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ip6dy4b-s {
  d: path("M14.5 3.5L17 2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l7sg0pb6g {
  d: path("M12 22C8.13401 22 5 18.866 5 15V10C5 6.13401 8.13401 3 12 3C15.866 3 19 6.13401 19 10V15C19 18.866 15.866 22 12 22Z");
}

.ltrgokn6u {
  d: path("M9.5 3.5L7 2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pb1o_xtkh {
  d: path("M5.29785 7.71909L3.50012 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rf84fqwne {
  d: path("M5.5 18.2002L3.5 19.0002");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uh-kdpqbj {
  d: path("M18.7021 7.71909L20.4999 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wdgiifbhr {
  d: path("M5 13H2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xuz371e7m {
  d: path("M18.5 18.2002L20.5 19.0002");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xzpga8tov {
  d: path("M19 13H22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
