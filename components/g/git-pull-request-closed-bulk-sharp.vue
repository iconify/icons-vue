<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v_qg2hb2n"/><path class="bc7dpdcnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-pull-request-closed-bulk-sharp" /></template>
<style>
.bc7dpdcnt {
  d: path("M17.707 3.293L19 4.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L20.414 6l1.293 1.293a.999.999 0 1 1-1.414 1.414L19 7.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L17.586 6l-1.293-1.293a.999.999 0 1 1 1.414-1.414M4 16V8a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0m14 0v-4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.v_qg2hb2n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m0 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0m14 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
