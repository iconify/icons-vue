<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5qaqmduo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-windows-rounded" /></template>
<style>
.n5qaqmduo {
  fill: currentColor;
  d: path("M11 19v-2H4.616q-.691 0-1.153-.462T3 15.385v-9.77q0-.69.463-1.152T4.615 4h14.77q.69 0 1.152.463T21 5.616v9.769q0 .69-.463 1.153T19.385 17H13v2h1.5q.214 0 .357.143T15 19.5t-.143.357T14.5 20h-5q-.213 0-.357-.143T9 19.5t.143-.357T9.5 19z");
}

</style>
