<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="jtuoc5b-g"/><path class="x2j7uwbre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-fat-lines-right-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jtuoc5b-g {
  d: path("M136 224v-48h-32V80h32V32l96 96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x2j7uwbre {
  d: path("m237.66 122.34l-96-96A8 8 0 0 0 128 32v40h-24a8 8 0 0 0-8 8v96a8 8 0 0 0 8 8h24v40a8 8 0 0 0 13.66 5.66l96-96a8 8 0 0 0 0-11.32M144 204.69V176a8 8 0 0 0-8-8h-24V88h24a8 8 0 0 0 8-8V51.31L220.69 128ZM48 80v96a8 8 0 0 1-16 0V80a8 8 0 0 1 16 0m32 0v96a8 8 0 0 1-16 0V80a8 8 0 0 1 16 0");
}

</style>
