<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cbvomiyis"/><path class="l_xr03cls"/><path class="cyo699t7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-histoire-opened" /></template>
<style>
.cbvomiyis {
  fill: var(--svg-color--a3aeff, #a3aeff);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.cyo699t7q {
  fill: var(--svg-color--b4fae2, #b4fae2);
  stroke: var(--svg-color--b4fae2, #b4fae2);
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-336px, 0.336px);
  d: path("m26.167 24.724l-1.565-7.265l-3.336 2.521zm-3.472-3.358l-4.9-4.743l1.564 7.272z");
}

.l_xr03cls {
  fill: var(--svg-color--34d399, #34d399);
  d: path("m15.301 12.965l12.044-.964a.327.327 0 0 1 .35.3l1.265 15.773a.32.32 0 0 1-.3.35l-12.044.964a.32.32 0 0 1-.35-.3L15 13.315a.32.32 0 0 1 .3-.35");
}

</style>
