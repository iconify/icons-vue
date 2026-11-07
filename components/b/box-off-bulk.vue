<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kse01kbli"/><path class="cfl4o3-hq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-off-bulk" /></template>
<style>
.cfl4o3-hq {
  d: path("m2.707 2.293l5.821 5.821l.017.016l13.162 13.163a.999.999 0 1 1-1.414 1.414L13 15.414v6.471a1 1 0 0 1-2 0v-8.471L7.238 9.653L2.717 7.42a1 1 0 0 1 .393-1.896L1.293 3.707a.999.999 0 1 1 1.414-1.414M21.283 7.42l-6.467 3.193a1 1 0 0 1-.885-1.793l6.466-3.193a1 1 0 0 1 1.441.961a1 1 0 0 1-.555.832");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kse01kbli {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m7.476 4.234l-.746-.747l4.384-2.165a2 2 0 0 1 .872-.207h.028c.303.003.6.073.872.207l8 3.951A2 2 0 0 1 22 7.066v9.868a2.02 2.02 0 0 1-.499 1.324Zm10.749 13.577l1.493 1.493l-6.832 3.374l-.004.002a2 2 0 0 1-.864.205h-.036a2 2 0 0 1-.868-.207l-8-3.951A2 2 0 0 1 2 16.934V7.066a2 2 0 0 1 1.114-1.793l1.722-.851Z");
}

</style>
