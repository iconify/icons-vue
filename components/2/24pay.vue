<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dbs_9wf7y"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:24pay" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dbs_9wf7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.297 36.894l3.422-19.414L24 30.52h12.862M13.427 17.537c.7-3.97 4.847-7.098 8.82-6.308c2.605.518 4.348 2.85 4.134 5.584c-.158 2.033-1.156 4.039-2.777 5.271c-3.004 2.283-12.466 8.436-12.466 8.436H24");
}

</style>
