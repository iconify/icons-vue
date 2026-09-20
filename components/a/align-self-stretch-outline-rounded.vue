<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ummve7m4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-self-stretch-outline-rounded" /></template>
<style>
.ummve7m4n {
  fill: currentColor;
  d: path("M3 22q-.425 0-.712-.288T2 21t.288-.712T3 20h18q.425 0 .713.288T22 21t-.288.713T21 22zm8.5-4.5q-.425 0-.712-.288T10.5 16.5V7q0-.425.288-.712T11.5 6h1q.425 0 .713.288T13.5 7v9.5q0 .425-.288.713t-.712.287zM3 4q-.425 0-.712-.288T2 3t.288-.712T3 2h18q.425 0 .713.288T22 3t-.288.713T21 4z");
}

</style>
