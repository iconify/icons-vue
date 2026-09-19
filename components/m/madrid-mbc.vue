<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nv10allba"/><path class="n936asbfv"/><path class="diznu1bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:madrid-mbc" /></template>
<style>
.diznu1bre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.19 38.688l21.848-6.848L18.5 9.312l-14 3.93z");
}

.n936asbfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.559 33.591l2.434 4.462L43.5 33.93L27.477 12.362l-6.22.879");
}

.nv10allba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.837 28.595v-8.644l4.327 8.654l4.327-8.641v8.641m12.547 3.235l-3.045 6.214M43.5 33.93l-.738 3.636l-3.561-2.223");
}

</style>
