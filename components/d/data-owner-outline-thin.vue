<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ejuwxub1t"/><path class="xlo0hdbks"/><path class="olmwgycdy"/><path class="ptw-mzbbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:data-owner-outline-thin" /></template>
<style>
.ejuwxub1t {
  d: path("M3 5a5 2.5 0 0 1 10 0v8a5 2.5 0 0 1 -10 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olmwgycdy {
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ptw-mzbbd {
  d: path("M13 21a4 4 0 0 1 8 0");
}

.xlo0hdbks {
  d: path("M3 5a5 2.5 0 0 0 10 0");
}

</style>
