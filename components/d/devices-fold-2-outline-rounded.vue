<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylaikiqsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:devices-fold-2-outline-rounded" /></template>
<style>
.ylaikiqsf {
  fill: currentColor;
  d: path("M17 21H7q-.825 0-1.412-.587T5 19V5q0-.825.588-1.412T7 3h10.6q.625 0 1.125.338t.725.912l2.4 6q.4 1-.187 1.875T20 13h-1v6q0 .825-.587 1.413T17 21m3-10l-2.4-6H7l2.4 6zm-3 8v-6H9.4q-.625 0-1.125-.337t-.725-.913L7 10.375V19zM13.5 8");
}

</style>
