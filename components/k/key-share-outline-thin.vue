<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a0z9iab1m"/><path class="e2nq-yvbg"/><path class="xidycypec"/><path class="drjiz3bcf"/><path class="o40l0bbgl"/><path class="val6zublh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:key-share-outline-thin" /></template>
<style>
.a0z9iab1m {
  d: path("M14 2h2.5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3h-9a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3H10");
}

.drjiz3bcf {
  d: path("M12 21h2.5");
}

.e2nq-yvbg {
  d: path("M12 15v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o40l0bbgl {
  d: path("M9 8.5h6");
}

.val6zublh {
  d: path("M12.5 6 15 8.5 12.5 11");
}

.xidycypec {
  d: path("M12 18h3");
}

</style>
