<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aec7lkj0a"/><path class="k7uw9bbwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-share-bulk-round" /></template>
<style>
.aec7lkj0a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.196 21.981a1 1 0 0 1-1.177-1.177l.935-4.673A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.k7uw9bbwb {
  d: path("M16.707 11.293a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L13.586 13H11a2 2 0 0 0-2 2a1 1 0 0 1-2 0c0-1.064.418-2.078 1.172-2.828A3.98 3.98 0 0 1 11 11h2.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414Z");
}

</style>
