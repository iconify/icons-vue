<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="o9moclbsx"/><path class="jv56upq0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-down-right-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jv56upq0e {
  d: path("m229.66 162.34l-48-48A8 8 0 0 0 168 120v40H88a48 48 0 0 1 0-96h88a8 8 0 0 0 0-16H88a64 64 0 0 0 0 128h80v40a8 8 0 0 0 13.66 5.66l48-48a8 8 0 0 0 0-11.32M184 196.69v-57.38L212.69 168Z");
}

.o9moclbsx {
  d: path("m224 168l-48 48v-96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
