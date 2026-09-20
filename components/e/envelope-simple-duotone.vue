<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="irtov08ks"/><path class="t9st6qbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:envelope-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.irtov08ks {
  d: path("m224 56l-96 88l-96-88Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t9st6qbdl {
  d: path("M224 48H32a8 8 0 0 0-8 8v136a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V56a8 8 0 0 0-8-8m-20.57 16L128 133.15L52.57 64ZM216 192H40V74.19l82.59 75.71a8 8 0 0 0 10.82 0L216 74.19z");
}

</style>
