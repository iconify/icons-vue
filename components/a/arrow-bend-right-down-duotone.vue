<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ts82jdzwx"/><path class="ts2xu3bxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-right-down-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ts2xu3bxv {
  d: path("M207.39 172.94A8 8 0 0 0 200 168h-40v-40A104.11 104.11 0 0 0 56 24a8 8 0 0 0 0 16a88.1 88.1 0 0 1 88 88v40h-40a8 8 0 0 0-5.66 13.66l48 48a8 8 0 0 0 11.32 0l48-48a8 8 0 0 0 1.73-8.72M152 212.69L123.31 184h57.38Z");
}

.ts82jdzwx {
  d: path("m200 176l-48 48l-48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
