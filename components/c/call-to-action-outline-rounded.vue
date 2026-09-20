<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v82gk9oxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:call-to-action-outline-rounded" /></template>
<style>
.v82gk9oxq {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-2h16V6H4zm0 0V6zm3.5-1h9q.625 0 1.063-.437T18 15.5t-.437-1.062T16.5 14h-9q-.625 0-1.062.438T6 15.5t.438 1.063T7.5 17");
}

</style>
