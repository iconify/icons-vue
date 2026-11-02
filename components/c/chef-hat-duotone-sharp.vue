<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y08cdsibg"/><path class="encmdp58l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chef-hat-duotone-sharp" /></template>
<style>
.encmdp58l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 15c-4.622-1.734-2.894-8.645 2-8a4 4 0 1 1 8 0c4.894-.645 6.622 6.266 2 8v6H6zm0 2h12");
}

.ft5dv1b6b {
  fill: none;
}

.y08cdsibg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 7a4 4 0 0 1 8 0c4.895-.638 6.62 6.259 2 8v6H6v-6c-4.62-1.741-2.895-8.638 2-8");
}

</style>
