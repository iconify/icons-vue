<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="w7gqnabxd"/><path class="nxgbg5cjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:fire-extinguisher-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nxgbg5cjo {
  d: path("m218.3 48.34l-60.68-18.2l30-15a8 8 0 0 0-7.2-14.29L134 24.05a80.08 80.08 0 0 0-78 80V208a8 8 0 0 0 16 0v-32h16v56a16 16 0 0 0 16 16h64a16 16 0 0 0 16-16V104a48.07 48.07 0 0 0-40-47.32V42.75l69.7 20.91a8 8 0 1 0 4.6-15.32M88 104v56H72v-56a64.07 64.07 0 0 1 56-63.48v16.16A48.07 48.07 0 0 0 88 104m80 128h-64v-56h64Zm0-128v56h-64v-56a32 32 0 0 1 64 0");
}

.w7gqnabxd {
  d: path("M176 168v64a8 8 0 0 1-8 8h-64a8 8 0 0 1-8-8v-64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
