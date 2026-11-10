<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zb-136byk"/><path clip-rule="evenodd" class="os2ejzbji"/><path class="wnoqcq_wf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:jerry-can-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.os2ejzbji {
  fill-rule: evenodd;
  d: path("M19 1C19.552 1 20 1.45 20 2V5H21C21.552 5 22 5.45 22 6V22C22 22.55 21.552 23 21 23H3C2.448 23 2 22.55 2 22V11C2 10.66 2.178 10.34 2.47 10.15L10.47 5.15C10.629 5.05 10.813 5 11 5H12V2C12 1.45 12.448 1 13 1H19ZM13.586 12H10.414L9.414 11L8 12.41L9 13.41V16.59L8 17.59L9.414 19L10.414 18H13.586L14.586 19L16 17.59L15 16.59V13.41L16 12.41L14.586 11L13.586 12ZM14 3V5H18V3H14Z");
}

.wnoqcq_wf {
  d: path("M7.971 1.85L8.998 3.57L3.028 7.15L2.001 5.43L7.971 1.85Z");
}

.zb-136byk {
  d: path("M13 14V16H11V14H13Z");
}

</style>
