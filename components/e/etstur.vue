<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="xn40h2bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:etstur" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.xn40h2bth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.166 27.429c.571.428 1.143.571 2.286.571h.571c1 0 1.857-.857 1.857-1.857s-.857-1.857-1.857-1.857h-1.286c-1 0-1.857-.857-1.857-1.857s.858-1.857 1.857-1.857h.572c1.286 0 1.857.143 2.286.571M23.925 18v8.571c0 .857.572 1.429 1.429 1.429h.429m-3.429-7.714h3.143m-5.092 6.285c-.428.857-1.428 1.429-2.428 1.429a2.866 2.866 0 0 1-2.857-2.857v-1.857a2.866 2.866 0 0 1 2.857-2.857a2.866 2.866 0 0 1 2.857 2.857v1H15.12");
}

</style>
