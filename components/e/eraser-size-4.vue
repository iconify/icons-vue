<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlca4_bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:eraser-size-4" /></template>
<style>
.tlca4_bln {
  fill: currentColor;
  d: path("M9.9 20q-2.45 0-4.175-1.725T4 14.1q0-1.15.425-2.238t1.3-1.962L9.9 5.725q.875-.875 1.962-1.3T14.1 4q2.45 0 4.175 1.725T20 9.9q0 1.15-.425 2.237t-1.3 1.963L14.1 18.275q-.875.875-1.962 1.3T9.9 20");
}

</style>
