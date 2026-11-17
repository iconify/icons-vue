<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l2fk5ab0b"/><path class="yss9owkyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-key-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l2fk5ab0b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 6a4 4 0 1 1 8 0a4 4 0 0 1-8 0m-.707 9.293l3-3C7.049 11.537 7.896 11 9 11h3c.942 0 1.827.439 2.394 1.191l1.899-1.898a3.121 3.121 0 1 1 4.414 4.414l-5 5C14.992 20.422 14.039 21 13 21H8a1 1 0 0 1-.707-.293l-4-4a1 1 0 0 1 0-1.414");
}

.yss9owkyw {
  d: path("M11.874 5H16V4a1 1 0 0 1 2 0a1 1 0 0 1 2 0v2a1 1 0 0 1-1 1h-7.126a4 4 0 1 1 0-2M10 6a2 2 0 1 0-3.999-.001A2 2 0 0 0 10 6m2 11h-2a1 1 0 0 1 0-2h2a.997.997 0 0 0 1-1a1 1 0 0 1 2 0a3 3 0 0 1-3 3m-2.293 3.293a.999.999 0 1 1-1.414 1.414l-6-6a.999.999 0 1 1 1.414-1.414Z");
}

</style>
