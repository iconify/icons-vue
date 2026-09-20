<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="v1zu3mb9h"/><circle class="qz-j4nozx"/><path class="pni6t7mzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:duet" /></template>
<style>
.pni6t7mzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.872 0 21.497 9.624 21.497 21.497c0 3.554-.863 6.907-2.39 9.86C40.885 25.382 33.172 19.129 24 19.129M24 45.5c-11.872 0-21.497-9.624-21.497-21.497c0-3.554.863-6.907 2.39-9.86C7.115 22.618 14.828 28.871 24 28.871");
}

.qz-j4nozx {
  cx: 24px;
  cy: 37.182px;
  r: 8.318px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v1zu3mb9h {
  cx: 24px;
  cy: 10.818px;
  r: 8.318px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
