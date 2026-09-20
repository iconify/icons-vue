<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hk-7c0bfl"/><path class="q-_bdy35o"/><path class="l3yq_fbub"/><path class="euvekjzkt"/><path class="ttx6bbv4v"/><path class="fem_64cmj"/><path class="z6x67ktzg"/><path class="xubfi0bjs"/><path class="bnhdslb0j"/><path class="ic_pehd5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:backoff-exponential-duotone-thin" /></template>
<style>
.bnhdslb0j {
  d: path("M19 8v6");
}

.euvekjzkt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fem_64cmj {
  d: path("M3 8v6");
}

.hk-7c0bfl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.l3yq_fbub {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q-_bdy35o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ttx6bbv4v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xubfi0bjs {
  d: path("M11 8v6");
}

.z6x67ktzg {
  d: path("M6 8v6");
}

</style>
