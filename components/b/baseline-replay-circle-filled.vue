<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo0j2s1tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-replay-circle-filled" /></template>
<style>
.eo0j2s1tb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m6 10c0 3.31-2.69 6-6 6s-6-2.69-6-6h2c0 2.21 1.79 4 4 4s4-1.79 4-4s-1.79-4-4-4v3L8 7l4-4v3c3.31 0 6 2.69 6 6");
}

</style>
