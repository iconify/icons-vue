<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro50vm1uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-help-fill-round" /></template>
<style>
.ro50vm1uc {
  fill: currentColor;
  d: path("M3 17v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l4 3.5A5 5 0 0 1 21 11.815V17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5m6.236-5.168A3 3 0 0 0 9 13a1 1 0 0 0 2 0a1.001 1.001 0 0 1 1.707-.707a1 1 0 0 1 .215 1.094A.99.99 0 0 1 12 14a1 1 0 0 0 0 2a3 3 0 1 0-2.764-4.168M12.01 17H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
