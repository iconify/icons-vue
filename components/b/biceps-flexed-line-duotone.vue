<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rdxknmmky"/><path class="jth4w6bry"/><path class="c74aedcjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:biceps-flexed-line-duotone" /></template>
<style>
.c74aedcjv {
  d: path("M9.78786 6.8307C8.30076 8.4 9.10076 12.2 8.22656 15.0268");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jth4w6bry {
  d: path("M11.4634 13.4258C12.6004 10.6 14.8004 9.7 17.0004 10C19.8004 10.4 21.6004 12.6 21.6004 15.3C21.6004 18.9 18.1004 21.5 12.8004 21.5C8.70039 21.5 5.10039 20.8 3.20039 19.3C2.60039 18.8 2.40039 18 2.40039 17.2C2.60039 12.2 3.30039 2.5 9.60039 2.5C11.6004 2.5 12.8004 3.6 12.8004 5C12.8004 6.2 11.9004 7 10.7004 7C9.80039 7 9.20039 6.6 8.90039 6");
}

.rdxknmmky {
  d: path("M7.40039 16C9.20039 13.4 12.4004 12.7 15.0004 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
