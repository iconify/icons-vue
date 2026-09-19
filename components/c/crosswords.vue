<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_qvydb-o"/><path class="bd_pzeehw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:crosswords" /></template>
<style>
.bd_pzeehw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.441 21.81l-3.253 10.143l-3.062-10.143l-3.254 10.143L21.81 21.81m19.33 19.138v-5.103l-2.743 3.445h3.381");
}

.j_qvydb-o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.5 6.5h24.241v12.12m-12.12 12.121H6.5V6.5m12.759 12.759H43.5V43.5H19.259zM16.707 9.052L9.052 19.195m7.655 0L9.052 9.052");
}

</style>
