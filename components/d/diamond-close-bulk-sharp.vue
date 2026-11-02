<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gfcx977il"/><path class="aiqmhrbjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-close-bulk-sharp" /></template>
<style>
.aiqmhrbjl {
  d: path("M10.707 9.293L12 10.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 12l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 13.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 12l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gfcx977il {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m17.707 17.707l-5 5a1 1 0 0 1-1.414 0l-10-10a1 1 0 0 1 0-1.414l10-10a1 1 0 0 1 1.414 0l10 10a1 1 0 0 1 0 1.414Z");
}

</style>
