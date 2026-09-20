<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzlbarbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:aod-tablet-outline-rounded" /></template>
<style>
.nzlbarbff {
  fill: currentColor;
  d: path("M8.75 11.5q-.325 0-.537-.213T8 10.75t.213-.537T8.75 10h6.5q.325 0 .538.213t.212.537t-.213.538t-.537.212zm1 3q-.325 0-.537-.213T9 13.75t.213-.537T9.75 13h4.5q.325 0 .538.213t.212.537t-.213.538t-.537.212zM3 20q-.825 0-1.412-.587T1 18V6q0-.825.588-1.412T3 4h18q.825 0 1.413.588T23 6v12q0 .825-.587 1.413T21 20zM4 6H3v12h1zm2 12h12V6H6zM20 6v12h1V6zm0 0h1zM4 6H3z");
}

</style>
