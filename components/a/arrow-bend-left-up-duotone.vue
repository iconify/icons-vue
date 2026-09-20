<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="dvcvswb4e"/><path class="qmlu71jco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-left-up-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dvcvswb4e {
  d: path("M152 80H56l48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qmlu71jco {
  d: path("M200 216a88.1 88.1 0 0 1-88-88V88h40a8 8 0 0 0 5.66-13.66l-48-48a8 8 0 0 0-11.32 0l-48 48A8 8 0 0 0 56 88h40v40a104.11 104.11 0 0 0 104 104a8 8 0 0 0 0-16M104 43.31L132.69 72H75.31Z");
}

</style>
