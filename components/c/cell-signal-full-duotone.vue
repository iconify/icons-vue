<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="qnpr_mqnd"/><path class="oqj5vw0ip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cell-signal-full-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oqj5vw0ip {
  d: path("M198.12 25.23a16 16 0 0 0-17.44 3.46l-160 160A16 16 0 0 0 32 216h160a16 16 0 0 0 16-16V40a15.94 15.94 0 0 0-9.88-14.77M192 200H32L192 40Z");
}

.qnpr_mqnd {
  d: path("M200 40v160a8 8 0 0 1-8 8H32a8 8 0 0 1-5.66-13.66l160-160A8 8 0 0 1 200 40");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
