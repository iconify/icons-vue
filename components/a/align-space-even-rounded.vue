<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4nog4qps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-space-even-rounded" /></template>
<style>
.x4nog4qps {
  fill: currentColor;
  d: path("M8 17q-.425 0-.712-.288T7 16v-1q0-.425.288-.712T8 14h8q.425 0 .713.288T17 15v1q0 .425-.288.713T16 17zm0-7q-.425 0-.712-.288T7 9V8q0-.425.288-.712T8 7h8q.425 0 .713.288T17 8v1q0 .425-.288.713T16 10zM3 22q-.425 0-.712-.288T2 21t.288-.712T3 20h18q.425 0 .713.288T22 21t-.288.713T21 22zM3 4q-.425 0-.712-.288T2 3t.288-.712T3 2h18q.425 0 .713.288T22 3t-.288.713T21 4z");
}

</style>
