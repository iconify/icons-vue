<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrtu_dbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:labs-outline-sharp" /></template>
<style>
.qrtu_dbhg {
  fill: currentColor;
  d: path("M12 22q-2.075 0-3.537-1.463T7 17V8H5V2h14v6h-2v9q0 2.075-1.463 3.538T12 22M7 6h10V4H7zm7.125 13.125Q15 18.25 15 17h-3v-2h3v-2h-3v-2h3V8H9v9q0 1.25.875 2.125T12 20t2.125-.875M7 6V4z");
}

</style>
