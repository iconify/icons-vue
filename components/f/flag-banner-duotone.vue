<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hk7oorbvv"/><path class="k2qyxh6qq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:flag-banner-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hk7oorbvv {
  d: path("m232 56l-45.71 96H40l48-48l-48-48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k2qyxh6qq {
  d: path("M238.76 51.73A8 8 0 0 0 232 48H40a8 8 0 0 0-5.66 13.66L76.69 104l-42.35 42.34A8 8 0 0 0 40 160h133.62l-28.84 60.56a8 8 0 1 0 14.44 6.88l80-168a8 8 0 0 0-.46-7.71M181.23 144H59.31l34.35-34.34a8 8 0 0 0 0-11.32L59.31 64h160Z");
}

</style>
