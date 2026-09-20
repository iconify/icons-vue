<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vfbrp6_ou"/><path class="sa-7frbqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:copy-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.sa-7frbqc {
  d: path("M216 32H88a8 8 0 0 0-8 8v40H40a8 8 0 0 0-8 8v128a8 8 0 0 0 8 8h128a8 8 0 0 0 8-8v-40h40a8 8 0 0 0 8-8V40a8 8 0 0 0-8-8m-56 176H48V96h112Zm48-48h-32V88a8 8 0 0 0-8-8H96V48h112Z");
}

.vfbrp6_ou {
  d: path("M216 40v128h-48V88H88V40Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
