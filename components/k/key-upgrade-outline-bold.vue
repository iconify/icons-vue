<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a0z9iab1m"/><path class="e2nq-yvbg"/><path class="xidycypec"/><path class="drjiz3bcf"/><path class="h59mhtbqo"/><path class="gc00z3www"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:key-upgrade-outline-bold" /></template>
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

.gc00z3www {
  d: path("m10 11.5 2 -2 2 2");
}

.h59mhtbqo {
  d: path("m10 8.5 2 -2 2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xidycypec {
  d: path("M12 18h3");
}

</style>
