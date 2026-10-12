<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wwdm07jbu"/><circle class="f1bpvi6as"/><circle class="xzbk_7bof"/><circle class="jksu-ji1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:distribution-center" /></template>
<style>
.f1bpvi6as {
  cx: 19px;
  cy: 4.75px;
  r: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jksu-ji1z {
  cx: 19px;
  cy: 19.25px;
  r: 1.5px;
}

.wwdm07jbu {
  d: path("M2.75 19v-8.7a1 1 0 0 1 .45-.83l3.5-2.33a1 1 0 0 1 1.1 0l3.5 2.33a1 1 0 0 1 .45.83V19Zm9-7h5.75M14 12l3.6-5.9M14 12l3.6 5.9");
}

.xzbk_7bof {
  cx: 19px;
  cy: 12px;
  r: 1.5px;
}

</style>
