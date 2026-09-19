<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shj43e71p"/><path class="elvi7109i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:easyrpg-player" /></template>
<style>
.elvi7109i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.109 15.36L29.2 9.317a.996.996 0 0 0-.115-1.518c-2.172-1.54-7.824-4.514-12.741 1.776c-5.634 7.208 2.096 14.311 7.466 17.411");
}

.shj43e71p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.092 33.407l-8.279-2.255a.996.996 0 0 0-1.257.859c-.248 2.651.002 9.033 7.908 10.146c9.06 1.276 11.346-8.97 11.346-15.17m10.42 5.205l2.186 8.297a.996.996 0 0 0 1.373.66c2.42-1.111 7.822-4.52 4.833-11.923c-3.425-8.483-13.442-5.34-18.812-2.24");
}

</style>
