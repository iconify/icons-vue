<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-4adradq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:egg-outline" /></template>
<style>
.p-4adradq {
  fill: currentColor;
  d: path("M7.71 18.222q-1.748-1.797-1.748-4.362q0-1.689.55-3.437q.552-1.748 1.43-3.182t1.945-2.347t2.094-.913q1.033 0 2.101.902t1.943 2.335t1.425 3.193t.55 3.449q0 2.565-1.753 4.362q-1.754 1.797-4.27 1.797T7.71 18.222m7.827-.704Q17 16.018 17 13.874q0-1.472-.478-3.037q-.478-1.566-1.215-2.865t-1.623-2.145q-.884-.846-1.7-.846q-.817 0-1.704.846q-.888.846-1.625 2.155t-1.216 2.874t-.478 3.01q0 2.151 1.463 3.652t3.557 1.501t3.556-1.5m-2.537-.5q.213 0 .356-.144t.144-.356t-.144-.356t-.356-.144q-1.458 0-2.48-1.02q-1.02-1.021-1.02-2.48q0-.212-.144-.356t-.357-.144t-.356.144t-.143.356q0 1.868 1.316 3.184T13 17.019M11.98 12");
}

</style>
