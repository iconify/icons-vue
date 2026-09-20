<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nzpsuduik"/><path class="vhnbtvbtn"/><path class="icg46ikti"/><path class="vshgwuurx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:embed-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.icg46ikti {
  d: path("M9.5 12 7 14.5 9.5 17");
}

.nzpsuduik {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.vshgwuurx {
  d: path("m14.5 12 2.5 2.5 -2.5 2.5");
}

</style>
