<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb-3kjb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:id-card" /></template>
<style>
.zb-3kjb8j {
  fill: currentColor;
  d: path("M14 13h5v-2h-5zm0-3h5V8h-5zm-9 6h8v-.55q0-1.125-1.1-1.787T9 13t-2.9.663T5 15.45zm5.413-4.587Q11 10.825 11 10t-.587-1.412T9 8t-1.412.588T7 10t.588 1.413T9 12t1.413-.587M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20z");
}

</style>
