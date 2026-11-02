<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lu6f09uxb"/><path class="jlxvahb-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:discord-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jlxvahb-b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-2-6h2.03L15 4c1.5.16 3.04.49 4.43 1.5c1.57 5.67 1.67 9.83 1.17 11.45C20 18.33 18.86 20 17.33 20c-.5 0-2-2-2-3c-1.83.6-4.83.6-6.66 0c0 1-1.5 3-2 3C5.14 20 4 18.33 3.4 16.95C2.9 15.33 3 11.17 4.57 5.5C5.96 4.49 7.5 4.16 9 4l.97 2Z");
}

.lu6f09uxb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13.404 5l.696-1.436a1 1 0 0 1 1.006-.558c1.779.19 3.442.617 4.912 1.685c.183.133.315.324.376.542c.672 2.43 1.189 4.914 1.394 7.43c.072.885.105 1.776.06 2.663c-.034.645-.102 1.3-.292 1.919q-.016.053-.039.104c-.734 1.689-2.134 3.65-4.187 3.651c-.83-.001-1.579-.941-2.007-1.552a7 7 0 0 1-.702-1.236c-.864.165-1.742.245-2.621.238a13.4 13.4 0 0 1-2.621-.238a7 7 0 0 1-.702 1.236C8.249 20.059 7.5 20.999 6.67 21c-2.053-.001-3.453-1.962-4.187-3.651a1 1 0 0 1-.039-.104c-.19-.619-.258-1.274-.292-1.919a20 20 0 0 1 .06-2.663c.205-2.516.722-5 1.394-7.43c.061-.218.193-.409.376-.542c1.47-1.068 3.133-1.495 4.912-1.685a1 1 0 0 1 1.006.558L10.596 5Z");
}

</style>
