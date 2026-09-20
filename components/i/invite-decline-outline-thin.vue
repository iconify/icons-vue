<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u9zbhwwpi"/><path class="er-rmmbme"/><path class="i-eao3sns"/><path class="b3d1hobxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:invite-decline-outline-thin" /></template>
<style>
.b3d1hobxs {
  d: path("m22 13 -4 4");
}

.er-rmmbme {
  d: path("M6 10V5h6v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-eao3sns {
  d: path("m18 13 4 4");
}

.u9zbhwwpi {
  d: path("M2 10v9h14v-9Z");
}

</style>
