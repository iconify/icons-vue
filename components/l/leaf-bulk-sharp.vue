<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vdv1j9pre"/><path class="axoe3mv6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-bulk-sharp" /></template>
<style>
.axoe3mv6l {
  d: path("M7.867 17.502q-.358.72-.601 1.488c-.12.376-.22.76-.276 1.151a1 1 0 0 1-1.607.646a1 1 0 0 1-.373-.928c.072-.501.197-.992.349-1.474q.301-.945.747-1.832a1 1 0 0 1 .062-.108c.815-1.221 1.715-2.391 2.741-3.443a18.6 18.6 0 0 1 3.567-2.854a1.001 1.001 0 0 1 1.048 1.704a16.5 16.5 0 0 0-3.183 2.546c-.925.949-1.737 2.004-2.474 3.104");
}

.cuyn6tgcc {
  fill: currentColor;
}

.vdv1j9pre {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.504 17.868a1 1 0 0 1-.372-.372a12 12 0 0 1-1.181-2.802c-1.025-3.797.464-7.143 3.875-9.055a12.5 12.5 0 0 1 2.833-1.135c2.413-.656 4.953-.725 7.432-.5c.48.044.861.425.905.905c.225 2.479.156 5.019-.5 7.432c-1.752 6.438-7.125 8.879-12.992 5.527");
}

</style>
