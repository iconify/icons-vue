<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vdv1j9pre"/><path class="rwzfih2ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rwzfih2ue {
  d: path("m3.293 19.293l9-9a.999.999 0 1 1 1.414 1.414l-9 9a.999.999 0 1 1-1.414-1.414");
}

.vdv1j9pre {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.504 17.868a1 1 0 0 1-.372-.372a12 12 0 0 1-1.181-2.802c-1.025-3.797.464-7.143 3.875-9.055a12.5 12.5 0 0 1 2.833-1.135c2.413-.656 4.953-.725 7.432-.5c.48.044.861.425.905.905c.225 2.479.156 5.019-.5 7.432c-1.752 6.438-7.125 8.879-12.992 5.527");
}

</style>
