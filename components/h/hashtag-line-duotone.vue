<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hyjon0btb"/><path class="t1in8db2h"/><path class="ogw7e4m-c"/><path class="fpn8si0az"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hashtag-line-duotone" /></template>
<style>
.fpn8si0az {
  d: path("M20 16H2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hyjon0btb {
  d: path("M10 3L5 21");
}

.ogw7e4m-c {
  d: path("M22 9H4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.t1in8db2h {
  d: path("M19 3L14 21");
}

</style>
