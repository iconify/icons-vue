<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ubpbu9mrb"/><path class="t1in8db2h"/><path class="s41he0bba"/><path class="m-5zcvb8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hashtag-broken" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-5zcvb8c {
  d: path("M20 16H2");
}

.s41he0bba {
  d: path("M22 9H4");
}

.t1in8db2h {
  d: path("M19 3L14 21");
}

.ubpbu9mrb {
  d: path("M10 3L8.75 7.5L8.61111 8L7.77778 11M6.94444 14L5 21");
}

</style>
