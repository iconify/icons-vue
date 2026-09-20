<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejp8gu9ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:blinds-2-closed-outline-sharp" /></template>
<style>
.ejp8gu9ul {
  fill: currentColor;
  d: path("M5 2h14q1.25 0 2.125.875T22 5v3h-2v14H4V8H2V5q0-1.25.875-2.125T5 2m.55 18h12.9l-1.4-2H16v.5q0 .425-.288.713T15 19.5t-.712-.288T14 18.5V18H6.95zM16 10h2.45l-1.4-2H16zM5 4q-.425 0-.712.288T4 5v1h16V5q0-.425-.288-.712T19 4zM4 6h16zm12 9h2.45l-1.4-2H16zM5.55 15H14v-2H6.95zm0-5H14V8H6.95z");
}

</style>
