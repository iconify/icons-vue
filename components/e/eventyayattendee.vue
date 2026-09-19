<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sewseni4n"/><path class="oxa-trvml"/><path class="kcsxjcwel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eventyayattendee" /></template>
<style>
.kcsxjcwel {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 4.5c-2.216 0-4 1.784-4 4v31c0 2.216 1.784 4 4 4h7.174a4.34 4.34 0 0 1 8.652 0H35.5c2.216 0 4-1.784 4-4v-31c0-2.216-1.784-4-4-4h-7.16a4.34 4.34 0 0 1-8.68 0z");
}

.oxa-trvml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 33.06a9.06 9.06 0 1 1 0-18.12a9.06 9.06 0 0 1 0 18.12");
}

.sewseni4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.08 25.88l7.84-3.76a4.35 4.35 0 1 0-2.021 5.81l.021-.01a4.35 4.35 0 0 0 2.4-3.16");
}

</style>
