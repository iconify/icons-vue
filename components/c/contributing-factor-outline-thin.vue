<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abnm6smsv"/><path class="kl155-_rt"/><path class="ct3cl0bsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:contributing-factor-outline-thin" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.ct3cl0bsi {
  d: path("M12 12.5V17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kl155-_rt {
  d: path("m8.5 9 3.5 3.5L15.5 9");
}

</style>
