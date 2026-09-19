<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4nlqur7n"/><path class="o2-5h5bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bolero-limonade-winkel" /></template>
<style>
.o2-5h5bbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.016 29.452a3.126 3.126 0 0 1 0 6.252h-5.158V23.2h5.158a3.126 3.126 0 0 1 0 6.252m0 0h-5.158");
}

.r4nlqur7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.459 43.5c7.235 0 13.101-5.866 13.101-13.101c0-10.253-10.002-22.591-12.623-25.622a.81.81 0 0 0-1.139-.08l-.08.08C20.132 7.82 10.358 20.146 10.358 30.4c0 7.235 5.865 13.101 13.1 13.101");
}

</style>
