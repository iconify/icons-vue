<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zt34abcdg"/><path class="dk_f1ab0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:external-link-alt-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dk_f1ab0x {
  d: path("M14 18h4V6H6v4a1 1 0 0 1-2 0V5a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1h-5a1 1 0 0 1 0-2m-4 2a1 1 0 0 1-2 0v-2.586l-4.293 4.293a.999.999 0 1 1-1.414-1.414L6.586 16H4a1 1 0 0 1 0-2h5a1 1 0 0 1 1 1Z");
}

.zt34abcdg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 19V5h14v14Z");
}

</style>
