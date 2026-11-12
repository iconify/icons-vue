<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rf0pcobwp"/><path class="gshkn9qqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:distort-linear" /></template>
<style>
.gshkn9qqt {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rf0pcobwp {
  stroke-linecap: round;
  d: path("M12 12C12 12 6 16 12 22M12 12C12 12 17 17 22 12M12 12C12 12 17 7 12 2M12 12C12 12 8 6 2 12");
}

</style>
