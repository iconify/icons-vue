<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ewrujue9y"/><path clip-rule="evenodd" class="isyhkdbji"/><path class="kupu6nl1f"/><path class="lescs2bvb"/><path class="lhj2dbcmt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:l2-background" /></template>
<style>
.ewrujue9y {
  fill: var(--svg-color--fc8800, #fc8800);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.isyhkdbji {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.47a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06");
}

.kupu6nl1f {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.96 15.501L8.306 7.294h9.34z");
}

.lescs2bvb {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.002 8.499l-4.65 8.207h9.341z");
}

.lhj2dbcmt {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.995 10.278L12.96 15.5l1.021-1.788L11.002 8.5z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
