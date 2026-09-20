<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n1d8w8_ef"/><g class="to-5kdesz"><path class="amnhwoh2g"/><path class="lw4f_pt4y"/><path class="is-ytvijl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-kash-15" /></template>
<style>
.amnhwoh2g {
  stroke-linecap: round;
  d: path("M39.9 19.856h-33m33-3.751v23.412a4 4 0 0 1-4 4h-25a4 4 0 0 1-4-4v-25a4 4 0 0 1 4-4h14.953");
}

.is-ytvijl {
  d: path("M39.9 16.105a3.985 3.985 0 1 0 0-7.97c-.086 0-.167.02-.253.025c-.653-2.124-2.608-3.677-4.946-3.677S30.41 6.036 29.755 8.16c-.085-.005-.166-.025-.252-.025a3.985 3.985 0 1 0 0 7.97z");
}

.lw4f_pt4y {
  stroke-linecap: round;
  d: path("M39.9 16.105v23.412a4 4 0 0 1-4 4h-25a4 4 0 0 1-4-4v-25a4 4 0 0 1 4-4h14.953m-12.96-3l.015 6");
}

.n1d8w8_ef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.602 27.465l2.8-1.54m0 0v11.2m4.218-.945c.773.648 1.523.945 3.398.945h.322a3.14 3.14 0 0 0 0-6.28h-3.72v-4.92h6.86");
}

.to-5kdesz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

</style>
