<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfdzqwb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:density-small-rounded" /></template>
<style>
.kfdzqwb-o {
  fill: currentColor;
  d: path("M4 22q-.425 0-.712-.288T3 21t.288-.712T4 20h16q.425 0 .713.288T21 21t-.288.713T20 22zm0-6q-.425 0-.712-.288T3 15t.288-.712T4 14h16q.425 0 .713.288T21 15t-.288.713T20 16zm0-6q-.425 0-.712-.288T3 9t.288-.712T4 8h16q.425 0 .713.288T21 9t-.288.713T20 10zm0-6q-.425 0-.712-.288T3 3t.288-.712T4 2h16q.425 0 .713.288T21 3t-.288.713T20 4z");
}

</style>
