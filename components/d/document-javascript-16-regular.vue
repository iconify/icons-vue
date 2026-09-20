<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y723fwd3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-javascript-16-regular" /></template>
<style>
.y723fwd3o {
  fill: currentColor;
  d: path("M3.5 10a.5.5 0 0 1 .5.5v3a1.5 1.5 0 0 1-3 0V13a.5.5 0 0 1 1 0v.5a.5.5 0 0 0 1 0v-3a.5.5 0 0 1 .5-.5m3.06 0c.414 0 .811.164 1.104.457l.19.19a.5.5 0 1 1-.708.707l-.189-.19A.56.56 0 0 0 6.561 11h-.134a.427.427 0 0 0-.19.809l.974.488A1.427 1.427 0 0 1 6.573 15H6.44a1.56 1.56 0 0 1-1.103-.457l-.19-.19a.5.5 0 1 1 .708-.707l.189.19A.56.56 0 0 0 6.44 14h.134a.427.427 0 0 0 .19-.809l-.974-.488A1.427 1.427 0 0 1 6.427 10zm2.03-9c.397.002.778.16 1.06.44l2.91 2.91c.28.282.438.663.44 1.06V13a2.006 2.006 0 0 1-2 2H8.54c.216-.296.36-.639.42-1H11a1 1 0 0 0 1-1V6H9.5A1.5 1.5 0 0 1 8 4.5V2H5a1 1 0 0 0-1 1v6.09a1.43 1.43 0 0 0-1 0V3a2.005 2.005 0 0 1 2-2zM9 4.5a.5.5 0 0 0 .5.5h2.29L9 2.21z");
}

</style>
