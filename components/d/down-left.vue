<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="p1r29onlb"/><path class="ym_fcjrpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:down-left" /></template>
<style>
.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.p1r29onlb {
  d: path("M7.707 16.707a1 1 0 0 1-1.414 0l-4-4a1 1 0 0 1 0-1.414l4-4a1 1 0 0 1 1.414 1.414L4.414 12l3.293 3.293a1 1 0 0 1 0 1.414");
}

.ym_fcjrpb {
  d: path("M12.75 11c.595 0 1.166-.238 1.588-.663A2.28 2.28 0 0 0 15 8.727V3a1 1 0 1 1 2 0v5.727a4.3 4.3 0 0 1-1.242 3.02A4.24 4.24 0 0 1 12.75 13H3a1 1 0 1 1 0-2z");
}

</style>
