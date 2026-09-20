<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r67keyb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:control-point-duplicate-outline-sharp" /></template>
<style>
.r67keyb7j {
  fill: currentColor;
  d: path("M14 16h2v-3h3v-2h-3V8h-2v3h-3v2h3zm-8 4.5q-2.725-.95-4.362-3.287T0 12t1.638-5.212T6 3.5v2.2q-1.85.875-2.925 2.575T2 12t1.075 3.725T6 18.3zm5.488-.213q-1.638-.712-2.85-1.924t-1.925-2.85T6 12t.713-3.512t1.925-2.85t2.85-1.925T15 3t3.513.713t2.85 1.924t1.925 2.85T24 12t-.712 3.513t-1.925 2.85t-2.85 1.925T15 21t-3.512-.712M15 19q2.925 0 4.963-2.037T22 12t-2.037-4.962T15 5t-4.962 2.038T8 12t2.038 4.963T15 19");
}

</style>
