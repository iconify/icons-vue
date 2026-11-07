<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="abfc6vb9w"/><path class="j16u3nbsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-smile-minus-corner-bulk-sharp" /></template>
<style>
.abfc6vb9w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 8h2.485a1 1 0 0 1 .943.667a10 10 0 1 1-19.006.458a9.98 9.98 0 0 1 7.553-6.924a9.86 9.86 0 0 1 4.659.152a1.002 1.002 0 0 1 .644 1.385A3 3 0 0 0 15 5c0 .799.312 1.558.879 2.121A2.98 2.98 0 0 0 18 8");
}

.cuyn6tgcc {
  fill: currentColor;
}

.j16u3nbsm {
  d: path("M22 4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2ZM9 8h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-4.753 6.316a4.65 4.65 0 0 0 5.046-1.023a.999.999 0 1 1 1.414 1.414a6.6 6.6 0 0 1-2.203 1.462a6.6 6.6 0 0 1-2.504.488a6.64 6.64 0 0 1-4.707-1.95a.999.999 0 1 1 1.414-1.414c.439.441.963.789 1.54 1.023");
}

</style>
