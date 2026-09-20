<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="zyhc4ob-x"/><path clip-rule="evenodd" class="z9nqsdprz"/><path class="vi-yg5enu"/><path class="txlqvcbnr"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:controller-circle" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.txlqvcbnr {
  d: path("M10 15a1 1 0 1 1-2 0v-4a1 1 0 0 1 2 0z");
}

.vi-yg5enu {
  d: path("M7 14a1 1 0 1 1 0-2h4a1 1 0 0 1 0 2z");
}

.z9nqsdprz {
  fill-rule: evenodd;
  d: path("M17.5 7h-9a5 5 0 0 0-5 5v2a5 5 0 0 0 5 5h9a5 5 0 0 0 5-5v-2a5 5 0 0 0-5-5m-12 5a3 3 0 0 1 3-3h9a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-9a3 3 0 0 1-3-3z");
}

.zyhc4ob-x {
  d: path("M15.25 13a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5m2 2.5a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5");
}

</style>
