<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jn42gv7lc"/><path class="xqjbvwbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:green-mango-dk" /></template>
<style>
.jn42gv7lc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.745 15.379c1.47-1.838 3.044-2.31 5.302-2.31S43.5 17.32 43.5 25.509s-7.82 15.642-13.017 15.642s-9.868-4.882-9.868-12.44s4.697-13.7 8.53-13.7c.682 0 1.6.367 1.6.367Z");
}

.xqjbvwbsr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.745 15.379c-1.181-2.546-2.02-4.567-2.047-8.53C18.226 8.056 6.73 16.953 4.5 20.444c3.78-2.283 15.17-8.136 20.078-9.71c-4.672 2.02-9.029 5.17-10.656 8.476c2.913-1.837 10.591-6.42 15.315-7.758");
}

</style>
