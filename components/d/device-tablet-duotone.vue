<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="q7bkl-p-k"/><path class="p0lupacnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:device-tablet-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p0lupacnf {
  d: path("M192 24H64a24 24 0 0 0-24 24v160a24 24 0 0 0 24 24h128a24 24 0 0 0 24-24V48a24 24 0 0 0-24-24M56 72h144v112H56Zm8-32h128a8 8 0 0 1 8 8v8H56v-8a8 8 0 0 1 8-8m128 176H64a8 8 0 0 1-8-8v-8h144v8a8 8 0 0 1-8 8");
}

.q7bkl-p-k {
  d: path("M208 64v128H48V64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
