<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs2o4ccql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dynamic-form-outline-rounded" /></template>
<style>
.hs2o4ccql {
  fill: currentColor;
  d: path("M4 11q-.825 0-1.412-.587T2 9V6q0-.825.588-1.412T4 4h8q.425 0 .713.288T13 5v5q0 .425-.288.713T12 11zm0-2h7V6H4zm0 11q-.825 0-1.412-.587T2 18v-3q0-.825.588-1.412T4 13h10q.425 0 .713.288T15 14v5q0 .425-.288.713T14 20zm0-2h9v-3H4zm13-7h-1q-.425 0-.712-.288T15 10V5q0-.425.288-.712T16 4h4.525q.525 0 .825.438t.1.937L20 9h.45q.55 0 .825.463t.075.962l-3.4 9.225q-.075.2-.225.275t-.325.025t-.288-.175T17 19.45zM4 9V6zm0 9v-3zM6.038 6.962Q5.825 6.75 5.5 6.75t-.537.213t-.213.537t.213.538t.537.212t.538-.213t.212-.537t-.213-.537m0 10.075q.213-.213.213-.538t-.213-.537t-.537-.213t-.537.213t-.213.537t.213.538t.537.212t.538-.213");
}

</style>
