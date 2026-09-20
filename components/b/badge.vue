<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt9whedxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:badge" /></template>
<style>
.jt9whedxo {
  fill: currentColor;
  d: path("M4.616 21q-.691 0-1.153-.462T3 19.385v-9.77q0-.69.463-1.152T4.615 8H10V4q0-.413.294-.706T11 3h2q.413 0 .706.294T14 4v4h5.385q.69 0 1.152.463T21 9.616v9.769q0 .69-.463 1.153T19.385 21zm1.692-3.577h5.384v-.142q0-.34-.186-.63t-.521-.451q-.481-.206-.974-.309q-.494-.103-1.011-.103t-1.01.103t-.975.309q-.334.16-.52.45t-.187.63zM14 15.885h4V15h-4zm-4.159-1.231q.351-.347.351-.842t-.346-.846t-.842-.35t-.845.346t-.351.841t.346.846t.841.351t.846-.347M14 13.5h4v-.885h-4zm-3-3.73h2V4h-2z");
}

</style>
