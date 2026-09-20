<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gay3fybmj"/><path class="tcuytc6ds"/><path class="obeew47lh"/><path class="uq_1facwu"/><path class="rsue96bcd"/><path class="q5jw2tb7h"/><path class="aut8y9hmn"/><path class="gwt34irsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:garden-chair-duotone-thin" /></template>
<style>
.aut8y9hmn {
  d: path("M7 12v7");
}

.gay3fybmj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gwt34irsi {
  d: path("M15 12v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.obeew47lh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q5jw2tb7h {
  d: path("m17 12 4 -4");
}

.rsue96bcd {
  d: path("M5 12h12");
}

.tcuytc6ds {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 12 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uq_1facwu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
