<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xn387sbqn"/><path class="amixg5sdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:briar-mailbox" /></template>
<style>
.amixg5sdm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.894 21.623V11.48a.964.964 0 0 0-.964-.965H13.07a.964.964 0 0 0-.964.965v10.142c0 .532.431.964.964.964h8.5v3.308h-1.631a.82.82 0 0 0-.616 1.359l4.06 4.636a.82.82 0 0 0 1.233 0l4.061-4.636a.82.82 0 0 0-.616-1.359h-1.63v-3.308h8.5a.964.964 0 0 0 .963-.964");
}

.xn387sbqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.357 5.5H10.643a4.007 4.007 0 0 0-4.008 4.007V33.55a4.007 4.007 0 0 0 4.008 4.008H33.16l6.177 4.683c.832.631 2.027.037 2.027-1.007V9.507A4.007 4.007 0 0 0 37.357 5.5");
}

</style>
