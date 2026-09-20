<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo39i1b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-windows" /></template>
<style>
.xo39i1b5m {
  fill: currentColor;
  d: path("M9 20v-1h2v-2H4.616q-.691 0-1.153-.462T3 15.385v-9.77q0-.69.463-1.152T4.615 4h14.77q.69 0 1.152.463T21 5.616v9.769q0 .69-.463 1.153T19.385 17H13v2h2v1z");
}

</style>
