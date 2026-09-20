<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq2yexb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:e-mobiledata-badge-rounded" /></template>
<style>
.oq2yexb7m {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm9-3.5q.213 0 .356-.143q.144-.143.144-.357t-.144-.357t-.356-.143H9.885v-3h3.73q.214 0 .357-.143q.144-.143.144-.357t-.144-.357t-.356-.143H9.885v-3h4.73q.214 0 .357-.143q.144-.143.144-.357t-.144-.357t-.356-.143H9.692q-.348 0-.577.23q-.23.23-.23.578v7.384q0 .349.23.578q.23.23.577.23z");
}

</style>
