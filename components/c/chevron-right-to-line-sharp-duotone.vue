<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jons1ob5m"/><path class="q7xwc7hma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevron-right-to-line-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jons1ob5m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 4V20H16V4H18ZM13.707 11.29C14.098 11.68 14.097 12.32 13.707 12.71L7.414 19L6 17.59L11.586 12L6 6.41L7.414 5L13.707 11.29Z");
}

.q7xwc7hma {
  d: path("M13.707 11.29C14.098 11.68 14.097 12.32 13.707 12.71L7.414 19L6 17.59L11.586 12L6 6.41L7.414 5L13.707 11.29Z");
}

</style>
