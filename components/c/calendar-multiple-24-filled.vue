<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjtlkj1mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-multiple-24-filled" /></template>
<style>
.sjtlkj1mw {
  fill: currentColor;
  d: path("m19.994 5.007l.004.121l.002.122v11.1A3.65 3.65 0 0 1 16.35 20H5.25a4 4 0 0 1-.243-.007A3.25 3.25 0 0 0 7.75 21.5h8.6a5.15 5.15 0 0 0 5.15-5.15v-8.6c0-1.153-.6-2.166-1.506-2.743M2 7.5v8.25A3.25 3.25 0 0 0 5.25 19h10.5A3.25 3.25 0 0 0 19 15.75V7.5zM5.25 2A3.25 3.25 0 0 0 2 5.25V6h17v-.75A3.25 3.25 0 0 0 15.75 2z");
}

</style>
