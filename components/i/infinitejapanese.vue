<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="v3wfvfjyk"/><path class="ylbarw5dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:infinitejapanese" /></template>
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

.v3wfvfjyk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.706 8.048c-1.746 10.97-1.898 20.7.476 28.939");
}

.ylbarw5dh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.988 13.765a160 160 0 0 0 24.353-1.132m-3.631 4.704c-3.312 9.734-7.69 17.186-14.53 19.173c-8.876 2.58-7.402-5.154-5.24-8.455c4.498-6.863 11.14-7.611 15.005-7.86c10.89-.699 13.399 8.68 10.837 12.505c-2.686 4.012-6.127 5.571-10.241 6.252");
}

</style>
