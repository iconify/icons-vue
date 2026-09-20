<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="q1b-r2bmk"/><path class="ns0vc4p0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hard-hat-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ns0vc4p0j {
  d: path("M224 152v-16a96.37 96.37 0 0 0-64-90.51V40a16 16 0 0 0-16-16h-32a16 16 0 0 0-16 16v5.49A96.37 96.37 0 0 0 32 136v16a16 16 0 0 0-16 16v24a16 16 0 0 0 16 16h192a16 16 0 0 0 16-16v-24a16 16 0 0 0-16-16m-16-16v16h-48V62.67A80.36 80.36 0 0 1 208 136m-64-96v112h-32V40Zm-96 96a80.36 80.36 0 0 1 48-73.33V152H48Zm176 56H32v-24h192z");
}

.q1b-r2bmk {
  d: path("M104 51.31V160H40v-24a88 88 0 0 1 64-84.69m48 0V160h64v-24a88 88 0 0 0-64-84.69");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
