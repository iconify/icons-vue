<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="op301-7iw"/><path class="qsymf5ppr"/></g><path class="ykyp60-nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:canara-epassbook" /></template>
<style>
.op301-7iw {
  d: path("m22.887 25.682l-2.171-.267l6.304-10.857l6.48 12.433l-6.799-.839");
}

.qsymf5ppr {
  d: path("m20.342 22.512l-5.842.976l7.486 5.954l6.392-8.274l-3.494.584");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ykyp60-nu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.5 4.5h-7a3.5 3.5 0 1 1-7 0h-7c-1.1 0-2 .9-2 2v35c0 1.1.9 2 2 2h7a3.5 3.5 0 1 1 7 0h7c1.1 0 2-.9 2-2v-35c0-1.1-.9-2-2-2");
}

</style>
