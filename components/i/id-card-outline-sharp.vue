<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx55otbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:id-card-outline-sharp" /></template>
<style>
.kx55otbhr {
  fill: currentColor;
  d: path("M14 13h5v-2h-5zm0-3h5V8h-5zm-9 6h8v-.55q0-1.125-1.1-1.787T9 13t-2.9.663T5 15.45zm5.413-4.587Q11 10.825 11 10t-.587-1.412T9 8t-1.412.588T7 10t.588 1.413T9 12t1.413-.587M2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
