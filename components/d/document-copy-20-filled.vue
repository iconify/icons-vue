<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r_0na2h4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-copy-20-filled" /></template>
<style>
.r_0na2h4x {
  fill: currentColor;
  d: path("M11 6.5V2H7.5A1.5 1.5 0 0 0 6 3.5v11A1.5 1.5 0 0 0 7.5 16h8a1.5 1.5 0 0 0 1.5-1.5V8h-4.5A1.5 1.5 0 0 1 11 6.5m1 0V2.25L16.75 7H12.5a.5.5 0 0 1-.5-.5M4 5a1 1 0 0 1 1-1v10.5A2.5 2.5 0 0 0 7.5 17H15a1 1 0 0 1-1 1H7.548A3.55 3.55 0 0 1 4 14.452z");
}

</style>
