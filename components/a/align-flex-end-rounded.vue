<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0pmo305k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-flex-end-rounded" /></template>
<style>
.g0pmo305k {
  fill: currentColor;
  d: path("M3 22q-.425 0-.712-.288T2 21t.288-.712T3 20h18q.425 0 .713.288T22 21t-.288.713T21 22zm8.5-4q-.425 0-.712-.288T10.5 17V5q0-.425.288-.712T11.5 4h1q.425 0 .713.288T13.5 5v12q0 .425-.288.713T12.5 18z");
}

</style>
