<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w51le_x_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:developing-tray" /></template>
<style>
.w51le_x_b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.318 9.25H4.682q-1.2 0-1.951.935q-.751.936-.49 2.108l1.222 5.5q.435 1.958 2.441 1.957h12.192q2.006.001 2.441-1.957l1.222-5.5q.261-1.172-.49-2.108t-1.951-.935M8.713 13.762q1.942.572 2.952.067q1.538-.769 4.046-.03q1.697.499 2.392.065q.126-.079.273-.104t.293.009q.145.034.266.12q.122.087.201.214q.039.062.065.131t.039.142t.01.147t-.019.146t-.047.139t-.073.127t-.097.111q-.054.051-.117.09q-1.266.792-3.61.102q-1.942-.572-2.952-.067q-1.538.769-4.046.03q-1.697-.499-2.392-.065q-.062.039-.131.065t-.142.039t-.147.01t-.146-.019t-.139-.047t-.127-.073t-.111-.097t-.09-.117t-.065-.131t-.039-.142t-.01-.147t.019-.146t.047-.139t.073-.127t.097-.111t.117-.09q1.266-.792 3.61-.102");
}

</style>
