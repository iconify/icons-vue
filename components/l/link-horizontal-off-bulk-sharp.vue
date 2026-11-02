<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j51f5fbyv"/><path class="f20hm5xtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-horizontal-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f20hm5xtb {
  d: path("M7 9a3 3 0 1 0 0 6h2a1 1 0 0 1 0 2H7A5 5 0 0 1 7 7h1a1 1 0 0 1 0 2Zm10-2a5 5 0 0 1 5 5c0 .466-.115.925-.331 1.338c-.229.446-.563.824-.849 1.234a1 1 0 1 1-1.64-1.144q.149-.21.307-.416c.142-.187.295-.378.403-.588A.9.9 0 0 0 20 12a2.98 2.98 0 0 0-.879-2.121A2.98 2.98 0 0 0 17 9h-2a1 1 0 0 1 0-2Z");
}

.j51f5fbyv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.707 11.293l10 10a.999.999 0 1 1-1.414 1.414L11.586 13H8a1 1 0 0 1 0-2h1.586L1.293 2.707a.999.999 0 1 1 1.414-1.414Z");
}

</style>
