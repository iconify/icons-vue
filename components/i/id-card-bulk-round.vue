<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n3ea6gw5u"/><path class="nsy2430mh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:id-card-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n3ea6gw5u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5Z");
}

.nsy2430mh {
  d: path("M5 10a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m8 0h3a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2M4 17c0-.468.141-.92.391-1.314c1.425-2.245 5.793-2.245 7.218 0c.25.394.391.846.391 1.314a1 1 0 0 1-2 0a.46.46 0 0 0-.08-.243c-.21-.331-.661-.535-1.024-.637A3.3 3.3 0 0 0 8 16a3.3 3.3 0 0 0-.896.12c-.363.102-.814.306-1.024.637A.46.46 0 0 0 6 17a1 1 0 0 1-2 0m10-3h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

</style>
