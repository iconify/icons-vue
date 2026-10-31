<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="upqjt-b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-open-person-20-filled" /></template>
<style>
.upqjt-b9e {
  fill: currentColor;
  d: path("M17.5 15a1.5 1.5 0 0 1 1.5 1.5c0 1.245-1 2.5-3.5 2.5S12 17.75 12 16.5a1.5 1.5 0 0 1 1.5-1.5zm-7.758-3.071a.5.5 0 0 0 .515 0l2.818-1.693a2.99 2.99 0 0 0 .198 3.774A2.5 2.5 0 0 0 11 16.5q0 .25.038.5H4.5A2.5 2.5 0 0 1 2 14.5V7.849q0-.271.07-.526zM15.5 10a2 2 0 1 1 0 4a2 2 0 0 1 0-4M9.743 2.071a.5.5 0 0 1 .514 0l6.772 4.063a2 2 0 0 1 .406.322L10 10.917L2.566 6.454a2 2 0 0 1 .405-.32z");
}

</style>
