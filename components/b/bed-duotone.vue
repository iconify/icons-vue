<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ya016tuhz"/><path class="tyg4u0bos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bed-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.tyg4u0bos {
  d: path("M216 72H32V48a8 8 0 0 0-16 0v160a8 8 0 0 0 16 0v-32h208v32a8 8 0 0 0 16 0v-96a40 40 0 0 0-40-40M32 88h72v72H32Zm88 72V88h96a24 24 0 0 1 24 24v48Z");
}

.ya016tuhz {
  d: path("M248 112v56H112V80h104a32 32 0 0 1 32 32");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
