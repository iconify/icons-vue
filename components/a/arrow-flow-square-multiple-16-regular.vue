<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="my3i6vbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-16-regular" /></template>
<style>
.my3i6vbjq {
  fill: currentColor;
  d: path("M13 4.503c.606.456 1 1.18 1 1.997v3A4.5 4.5 0 0 1 9.5 14h-3c-.817 0-1.54-.394-1.996-1H9.5A3.5 3.5 0 0 0 13 9.5zM9.5 2A2.5 2.5 0 0 1 12 4.5v5A2.5 2.5 0 0 1 9.5 12h-5A2.5 2.5 0 0 1 2 9.5V7.434c.16.04.327.066.5.066s.34-.025.5-.066V9.5A1.5 1.5 0 0 0 4.5 11h5A1.5 1.5 0 0 0 11 9.5v-5A1.5 1.5 0 0 0 9.5 3h-5c-.514 0-.967.258-1.237.651a2 2 0 0 0-1.067-.126A2.5 2.5 0 0 1 4.5 2zm-7 2.5c.37 0 .692.201.865.5h.385a3 3 0 0 1 2.4 1.2a2 2 0 0 0 1.6.8h.543L7.146 5.854a.5.5 0 1 1 .708-.708l2 2a.5.5 0 0 1 0 .708l-2 2a.5.5 0 1 1-.708-.708L8.293 8H7.75a3 3 0 0 1-2.4-1.2a2 2 0 0 0-1.6-.8h-.385A.999.999 0 0 1 1.5 5.5a1 1 0 0 1 1-1");
}

</style>
