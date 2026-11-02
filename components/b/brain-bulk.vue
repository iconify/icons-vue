<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="btfyv--hm"/><path class="de559zl6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brain-bulk" /></template>
<style>
.btfyv--hm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 3.352a4 4 0 0 1 7.002 2.647a4.98 4.98 0 0 1 1.918 4.896A5.006 5.006 0 0 1 21.001 17A5.001 5.001 0 0 1 12 20.003A5.002 5.002 0 0 1 2.999 17a5.006 5.006 0 0 1 .081-6.105a4.98 4.98 0 0 1 1.918-4.896A4.004 4.004 0 0 1 12 3.352");
}

.cuyn6tgcc {
  fill: currentColor;
}

.de559zl6j {
  d: path("M13 9.937c.088.677.352 1.32.764 1.865a3.93 3.93 0 0 0 1.629 1.278a1 1 0 0 1-.786 1.84A6 6 0 0 1 13 13.91V17a1 1 0 0 1-2 0v-3.09a6 6 0 0 1-1.607 1.01a1 1 0 0 1-.786-1.84A4 4 0 0 0 11 9.937V6a1 1 0 0 1 2 0Z");
}

</style>
