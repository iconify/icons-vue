<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c8g33-tpk"/><path class="r-behm4vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iod-connect" /></template>
<style>
.c8g33-tpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.404 11.272a14.6 14.6 0 0 0-2.116-3.583c-2.824-3.532-10.149-3.205-14.995 1.718C18.953 4.484 11.651 3.53 6.8 11.179c-3.824 6.027-1.016 12.83.712 18.275c.8 2.52 2.42 5.835 4.13 8.532c.635-8.833 5.777-12.435 14.671-14.402c8.427-1.864 17.553-4.677 16.75-12.984");
}

.r-behm4vz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.4 15.04c.771 5.742-.637 10.261-2.51 14.957c-1.82 4.56-4.255 10.003-8.235 12.213c-.511.284-1.074.325-1.557-.578c-.582-1.091-1.699-8.156-6.38-8.132c-3.005.016-5.047 4.145-5.56 7.384c-.157.985-.476 1.614-1.748 1.778c-.743.095-1.775-.732-2.885-2.068");
}

</style>
