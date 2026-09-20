<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esjsmfhfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-stacks-rounded" /></template>
<style>
.esjsmfhfd {
  fill: currentColor;
  d: path("M13 3.125V7h7.9q.475 0 .75.313t.275.687q0 .25-.125.488t-.4.387l-8.45 4.6q-.45.25-.95.25t-.95-.25l-8.45-4.6q-.275-.15-.388-.375T2.1 8t.113-.5t.387-.375l8.925-4.875q.25-.125.525-.112t.475.137t.338.35t.137.5m-1 12.6l7.85-4.275q.05-.025.475-.125q.425 0 .713.288t.287.712q0 .275-.125.5t-.4.375l-7.85 4.275q-.225.125-.462.188t-.488.062t-.488-.062t-.462-.188L3.2 13.2q-.275-.15-.4-.375t-.125-.5q0-.425.288-.712t.712-.288q.125 0 .238.038t.237.087zm0 4l7.85-4.275q.05-.025.475-.125q.425 0 .713.288t.287.712q0 .275-.125.5t-.4.375l-7.85 4.275q-.225.125-.462.188t-.488.062t-.488-.062t-.462-.188L3.2 17.2q-.275-.15-.4-.375t-.125-.5q0-.425.288-.712t.712-.288q.125 0 .238.038t.237.087z");
}

</style>
