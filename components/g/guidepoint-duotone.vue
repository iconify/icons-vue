<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gsuql2g9o"/><path class="qkt00tbwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:guidepoint-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gsuql2g9o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 8C7.2091 8 9 9.79 9 12C9 14.21 7.2091 16 5 16C2.7909 16 1 14.21 1 12C1 9.79 2.7909 8 5 8ZM19 8C21.2091 8 23 9.79 23 12C23 14.21 21.2091 16 19 16C16.7909 16 15 14.21 15 12C15 9.79 16.7909 8 19 8Z");
}

.qkt00tbwh {
  d: path("M16 11C16.5523 11 17 11.45 17 12C17 12.55 16.5523 13 16 13H8C7.4477 13 7 12.55 7 12C7 11.45 7.4477 11 8 11H16Z");
}

</style>
