<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inday_qzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-very-low-outline" /></template>
<style>
.inday_qzg {
  fill: currentColor;
  d: path("M5 17q-.425 0-.712-.288T4 16v-2H2v-4h2V8q0-.425.288-.712T5 7h16q.425 0 .713.288T22 8v8q0 .425-.288.713T21 17zm1-2h13V9H6z");
}

</style>
