<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t6kisabuh"/><path class="cluu9-b5o"/><path class="aj1uncbqw"/><path class="kwvl-5zwd"/><path class="mtvwri8au"/><path class="a1ch8_mho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:couple-duotone-thin" /></template>
<style>
.a1ch8_mho {
  d: path("M12.5 18a4.5 4.5 0 0 1 9 0");
}

.aj1uncbqw {
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.cluu9-b5o {
  fill: currentColor;
  d: path("M14 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwvl-5zwd {
  d: path("M2.5 16a4.5 4.5 0 0 1 9 0");
}

.mtvwri8au {
  d: path("M14 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.t6kisabuh {
  fill: currentColor;
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
