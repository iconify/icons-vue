<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="pmr_u1bhp"/><path class="q4tp_6w_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-down-left-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pmr_u1bhp {
  d: path("M96 128v96l-48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q4tp_6w_p {
  d: path("M192 24a8 8 0 0 0-8 8v136h-80v-40a8 8 0 0 0-13.66-5.66l-48 48a8 8 0 0 0 0 11.32l48 48A8 8 0 0 0 104 224v-40h88a8 8 0 0 0 8-8V32a8 8 0 0 0-8-8M88 204.69L59.31 176L88 147.31Z");
}

</style>
