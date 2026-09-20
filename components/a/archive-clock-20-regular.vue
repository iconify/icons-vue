<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="d2zdb4bdt"/><path class="cs15u60_i"/><path class="vjghjmb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-clock-20-regular" /></template>
<style>
.cs15u60_i {
  d: path("M16.25 3c.966 0 1.75.784 1.75 1.75v1.5a1.75 1.75 0 0 1-1 1.582v1.769a5.5 5.5 0 0 0-1-.393V8H4v6a2 2 0 0 0 2 2h3.208q.149.524.394 1H6a3 3 0 0 1-3-3V7.832A1.75 1.75 0 0 1 2 6.25v-1.5C2 3.784 2.784 3 3.75 3zM3.75 4a.75.75 0 0 0-.75.75v1.5c0 .414.336.75.75.75h12.5a.75.75 0 0 0 .75-.75v-1.5a.75.75 0 0 0-.75-.75z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.d2zdb4bdt {
  d: path("M19 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0M14.5 12a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H16a.5.5 0 0 0 0-1h-1v-1.5a.5.5 0 0 0-.5-.5");
}

.vjghjmb9g {
  d: path("M11.34 10a5.5 5.5 0 0 0-1.082 1H8.5a.5.5 0 0 1 0-1z");
}

</style>
