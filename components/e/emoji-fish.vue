<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="yti3afbtw"/><path class="uqn2vdb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-fish" /></template>
<style>
.uqn2vdb3m {
  d: path("M26.76 20.028s-4.251 2.835-.708 7.795");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yti3afbtw {
  d: path("M9.122 24.607S5.501 21.2 6.241 16.76s9.62.74 10.36 4.44c0 0 2.22-3.7 5.92-4.44c0 0-.74-3.7 0-5.92c0 0 8.14-2.96 11.1 4.44c0 0 8.139 1.48 8.879 8.14l-2.22 1.48l1.942 1.665s-.089 4.947-8.415 7.19c0 0-1.667 5.204-7.587 3.724l.74-3.7s-4.44.74-10.36-5.92c0 0-2.22 6.66-11.099 5.18c0 0-.157-5.766 3.621-8.432");
}

</style>
