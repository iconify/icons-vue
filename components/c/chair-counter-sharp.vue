<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n05q3mxvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chair-counter-sharp" /></template>
<style>
.n05q3mxvn {
  fill: currentColor;
  d: path("M7 22v-1.5q.9-.625 1.913-.975T11 19.05V17H8v-2h3V9H8.45L8.1 8H4V6.125Q4 4.4 5.15 3.2T8 2h8q1.7 0 2.85 1.2T20 6.125V8h-4.1l-.35 1H13v6h3v2h-3v2.05q1.075.125 2.088.475T17 20.5V22z");
}

</style>
