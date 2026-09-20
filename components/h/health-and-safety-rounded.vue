<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8u7qyb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:health-and-safety-rounded" /></template>
<style>
.c8u7qyb0t {
  fill: currentColor;
  d: path("M10.5 13v1.5q0 .425.288.713t.712.287h1q.425 0 .713-.288t.287-.712V13H15q.425 0 .713-.288T16 12v-1q0-.425-.288-.712T15 10h-1.5V8.5q0-.425-.288-.712T12.5 7.5h-1q-.425 0-.712.288T10.5 8.5V10H9q-.425 0-.712.288T8 11v1q0 .425.288.713T9 13zm1.175 8.875q-.15-.025-.3-.075Q8 20.675 6 17.637T4 11.1V6.375q0-.625.363-1.125t.937-.725l6-2.25q.35-.125.7-.125t.7.125l6 2.25q.575.225.938.725T20 6.375V11.1q0 3.5-2 6.538T12.625 21.8q-.15.05-.3.075T12 21.9t-.325-.025");
}

</style>
