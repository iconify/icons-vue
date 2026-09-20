<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0fwv7bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dishwasher-outline-sharp" /></template>
<style>
.d0fwv7bta {
  fill: currentColor;
  d: path("M5 11v8h14v-8zm0-2h14V5H5zm7 9q-.825 0-1.412-.587T10 16q0-.675.375-1.437T12 12q1.25 1.8 1.625 2.563T14 16q0 .825-.587 1.413T12 18m5.713-10.288Q18 7.425 18 7t-.288-.712T17 6t-.712.288T16 7t.288.713T17 8t.713-.288M3 21V3h18v18zM5 9V5z");
}

</style>
