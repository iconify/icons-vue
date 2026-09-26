<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ner24ccnr"/><path class="cohiy9ycb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-half-duotone" /></template>
<style>
.cohiy9ycb {
  d: path("M12 19C15.866 19 19 15.866 19 12C19 8.134 15.866 5 12 5C11.4477 5 11 5.4477 11 6L11 18C11 18.5523 11.4477 19 12 19Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ner24ccnr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.92487 23 1 18.0751 1 12C1 5.92487 5.92487 1 12 1C18.0751 1 23 5.92487 23 12Z");
}

</style>
