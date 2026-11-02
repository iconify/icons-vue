<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ou5c_6b_n"/><path class="rf1lhxbwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ou5c_6b_n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 21H5a1 1 0 0 1-1-1V6a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v14a1 1 0 0 1-1 1");
}

.rf1lhxbwv {
  d: path("m9.293 12.293l3-3a2.414 2.414 0 0 1 3.414 0l3 3C19.422 13.008 20 13.962 20 15v4h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h5v-4c0-1.039.577-1.991 1.293-2.707M18 19v-4c0-.467-.389-.975-.707-1.293l-3-3a.415.415 0 0 0-.586 0l-3 3c-.315.315-.707.825-.707 1.293v4Z");
}

</style>
