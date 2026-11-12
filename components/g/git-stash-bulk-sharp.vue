<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dj-hugbqi"/><path class="orn502skl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-stash-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dj-hugbqi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

.orn502skl {
  d: path("M11 8a1 1 0 0 1 2 0v4.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L11 12.586Zm9 6a1 1 0 0 1 2 0v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-7a1 1 0 0 1 2 0v6h16Z");
}

</style>
