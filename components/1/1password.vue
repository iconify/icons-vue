<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="jkcz-ye0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:1password" /></template>
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

.jkcz-ye0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.583 9.42h-5.166a1 1 0 0 0-1 1v6l2.293 2.293a1 1 0 0 1 0 1.415l-2.293 2.293V37.58a1 1 0 0 0 1 1h5.166a1 1 0 0 0 1-1v-6l-2.293-2.293a1 1 0 0 1 0-1.415l2.293-2.292V10.42a1 1 0 0 0-1-1");
}

</style>
