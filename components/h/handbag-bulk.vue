<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lvv8dnbcv"/><path class="r1ciqdbuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handbag-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lvv8dnbcv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 7h10c1.608 0 2.801 1.348 2.992 2.876l1 8c.121.968-.116 2.126-.925 2.752A1.75 1.75 0 0 1 19 21H5c-.389 0-.759-.135-1.067-.372c-.809-.626-1.046-1.784-.925-2.752l1-8C4.199 8.348 5.392 7 7 7");
}

.r1ciqdbuo {
  d: path("M7.393 6.053A5 5 0 0 1 17 8a1 1 0 0 1-2 0a2.998 2.998 0 0 0-4.962-2.269A3 3 0 0 0 9 8a1 1 0 0 1-2 0a5 5 0 0 1 .393-1.947");
}

</style>
