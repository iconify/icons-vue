<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s2h6xmb8a"/><path class="okdait3_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.okdait3_e {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-20-20a.999.999 0 1 1 1.414-1.414M22 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

.s2h6xmb8a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m6 6l12 12H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1Zm13 8.757L10.243 6H18a1 1 0 0 1 1 1Z");
}

</style>
