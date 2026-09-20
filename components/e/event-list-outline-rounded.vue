<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anj2msb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:event-list-outline-rounded" /></template>
<style>
.anj2msb9x {
  fill: currentColor;
  d: path("M15.616 20q-.402 0-.701-.299t-.3-.701v-4.384q0-.402.3-.701t.7-.3H20q.402 0 .701.3t.299.7V19q0 .402-.299.701T20 20zm0-1H20v-4.384h-4.384zM3.5 17.308q-.213 0-.357-.144T3 16.809t.143-.357t.357-.143h7.23q.214 0 .358.143t.143.357t-.143.356t-.357.144zm12.116-6.924q-.402 0-.701-.299t-.3-.7V5q0-.402.3-.701t.7-.299H20q.402 0 .701.299T21 5v4.385q0 .401-.299.7t-.701.3zm0-1H20V5h-4.384zM3.5 7.692q-.213 0-.357-.143T3 7.192t.143-.356t.357-.144h7.23q.214 0 .358.144t.143.356t-.143.357t-.357.143zm14.308-.5");
}

</style>
