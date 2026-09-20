<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2iqfkfmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-start-square-outline-rounded" /></template>
<style>
.t2iqfkfmh {
  fill: currentColor;
  d: path("M4 15.5h7v-7H4zm-1 2q-.425 0-.712-.288T2 16.5v-9q0-.425.288-.712T3 6.5h9q.425 0 .713.288T13 7.5V11h8q.425 0 .713.288T22 12t-.288.713T21 13h-8v3.5q0 .425-.288.713T12 17.5zM7.5 12");
}

</style>
