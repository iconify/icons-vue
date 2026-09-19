<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="v3tcsqbdd"/><g class="n1mjunbsu"><path class="b9-rb9bfb"/><path class="jw4pnwbhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:baby-symbol" /></template>
<style>
.b9-rb9bfb {
  d: path("M37 19.5c0 1.2-1.2 2.5-2.5 2.5h-5c-1.2 0-2.5-1.2-2.5-2.5v-5c0-1.2 1.2-2.5 2.5-2.5h5c1.2 0 2.5 1.2 2.5 2.5zM31 41l-5-3l-3 7l3 7l3-1l-2-6zm2 0l5-3l3 7l-3 7l-3-1l2-6z");
}

.jw4pnwbhi {
  d: path("M36 24h-8.1L20 21l-1 2l7 5v6q0 3 3 3h6q3 0 3-3v-6l7-5l-1-2z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.v3tcsqbdd {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--eda454, #eda454);
}

</style>
