<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ahod4jbhz"/><path class="aaogxinni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:exit-bulk-round" /></template>
<style>
.aaogxinni {
  d: path("M17 22H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h10c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 22 7a1 1 0 0 1-2 0a3 3 0 0 0-3-3H7a3 3 0 0 0-3 3v10a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3a1 1 0 0 1 2 0a5 5 0 0 1-1.464 3.536A4.98 4.98 0 0 1 17 22m-2.707-7.707L15.586 13H8a1 1 0 0 1 0-2h7.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

.ahod4jbhz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
