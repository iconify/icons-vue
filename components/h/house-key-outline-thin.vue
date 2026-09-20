<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cib2dlbwm"/><path class="zrdou8b0n"/><path class="buon2iihn"/><path class="q8xy9tkjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:house-key-outline-thin" /></template>
<style>
.buon2iihn {
  d: path("M16 12v4");
}

.cib2dlbwm {
  d: path("M4 15v-5l4 -4 4 4v5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q8xy9tkjr {
  d: path("M20 12v4");
}

.zrdou8b0n {
  d: path("M12 12h9");
}

</style>
