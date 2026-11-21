<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w7ht_ebft"/><path class="bpz71sblx"/><path class="dt639lb0s"/><path class="pvtzpwzvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:footprints-line-duotone" /></template>
<style>
.bpz71sblx {
  d: path("M7.00061 13.2C8.40061 13.2 9.10061 14.1 9.00061 15.3C8.90061 16.5 8.00061 17.3 6.90061 17.3C5.70061 17.3 4.90061 16.4 5.00061 15.2C5.10061 14 5.80061 13.2 7.00061 13.2Z");
}

.dt639lb0s {
  d: path("M16.8002 6.70001C14.8002 6.70001 13.8002 8.50001 14.2002 11.1C14.6002 13.4 15.3002 15 16.8002 15C18.3002 15 19.1002 13.6 19.5002 11.4C20.0002 8.80001 18.8002 6.70001 16.8002 6.70001Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pvtzpwzvl {
  d: path("M16.9996 17.4C15.5996 17.4 14.8996 18.3 14.9996 19.5C15.0996 20.7 15.9996 21.5 17.0996 21.5C18.2996 21.5 19.0996 20.6 18.9996 19.4C18.8996 18.2 18.1996 17.4 16.9996 17.4Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.w7ht_ebft {
  d: path("M7.20006 2.5C9.20006 2.5 10.2001 4.3 9.80006 6.9C9.40006 9.2 8.70006 10.8 7.20006 10.8C5.70006 10.8 4.90006 9.4 4.50006 7.2C4.00006 4.6 5.20006 2.5 7.20006 2.5Z");
}

</style>
