<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ft030md1w"/><path class="mv2usmo_g"/><path class="xrmojginc"/><path class="skbifdbcx"/><path class="p87z9hb2j"/><path class="x3u_7ebsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-upgrade-duotone-thin" /></template>
<style>
.ft030md1w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mv2usmo_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 16 4.5 -4.5L21 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p87z9hb2j {
  d: path("m12 16 4.5 -4.5L21 16");
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.x3u_7ebsy {
  d: path("m12 20.5 4.5 -4.5 4.5 4.5");
}

.xrmojginc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 20.5 4.5 -4.5 4.5 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
