<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="naudy1b1k"/><path class="x67_elb1a"/><path class="ef5tcc6_c"/><path class="me6k632rv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:luggage-tag-outline-thin" /></template>
<style>
.ef5tcc6_c {
  d: path("M4 16h14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.me6k632rv {
  d: path("M4 20h10");
}

.naudy1b1k {
  d: path("M6 4h10l4 4 -4 4H6Z");
}

.x67_elb1a {
  d: path("M8 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
