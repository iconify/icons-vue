<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t10dpvblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grid-on-rounded" /></template>
<style>
.t10dpvblp {
  fill: currentColor;
  d: path("M5.616 20h3.059v-4.656H4v3.04q0 .667.475 1.142t1.14.474m4.06 0h4.65v-4.656h-4.65zm5.65 0h3.06q.666 0 1.14-.475t.475-1.14v-3.04h-4.675zM4 14.344h4.675V9.656H4zm5.675 0h4.65V9.656h-4.65zm5.65 0H20V9.656h-4.675zM4 8.656h4.675V4h-3.06q-.666 0-1.14.475T4 5.615zm5.675 0h4.65V4h-4.65zm5.65 0H20v-3.04q0-.667-.475-1.141T18.386 4h-3.06z");
}

</style>
