<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkh6f026t"/><path class="vk-tazw8e"/><path class="wcuwprbdu"/><path class="xvakw33rf"/><path class="huxev8b1a"/><path class="k6nj2fbya"/><path class="sixdm4bhp"/><path class="k62k_4bsl"/><path class="n7wfhbrgu"/><path class="cxodqhtoo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:log-stream-duotone-regular" /></template>
<style>
.cxodqhtoo {
  d: path("m19 17 2 2 -2 2");
}

.huxev8b1a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 17 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k62k_4bsl {
  d: path("M3 13h16");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.mkh6f026t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n7wfhbrgu {
  d: path("M3 17h11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sixdm4bhp {
  d: path("M3 9h14");
}

.vk-tazw8e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wcuwprbdu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 13h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xvakw33rf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
