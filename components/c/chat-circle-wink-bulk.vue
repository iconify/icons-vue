<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aec7lkj0a"/><path class="gcmm7nf4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-wink-bulk" /></template>
<style>
.aec7lkj0a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.196 21.981a1 1 0 0 1-1.177-1.177l.935-4.673A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gcmm7nf4h {
  d: path("M9.01 8a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2ZM16 8a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm-5.753 6.316a4.65 4.65 0 0 0 5.046-1.023a.999.999 0 1 1 1.414 1.414a6.6 6.6 0 0 1-2.203 1.462a6.6 6.6 0 0 1-2.504.488a6.64 6.64 0 0 1-4.707-1.95a.999.999 0 1 1 1.414-1.414c.439.441.963.789 1.54 1.023");
}

</style>
