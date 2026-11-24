<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mrw7wccdy"/><path class="xv4_3nbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-open-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mrw7wccdy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 8h16a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1");
}

.xv4_3nbwz {
  d: path("M9 7v2a1 1 0 0 1-2 0V7a5.001 5.001 0 0 1 9.077-2.896c.121.171.267.377.334.575a1 1 0 0 1-1.813.821q-.038-.066-.08-.13A3 3 0 0 0 12 4c-.799 0-1.558.312-2.121.879A2.98 2.98 0 0 0 9 7m1.158 7.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
