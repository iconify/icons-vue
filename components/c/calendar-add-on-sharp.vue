<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjcfirb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calendar-add-on-sharp" /></template>
<style>
.sjcfirb2w {
  fill: currentColor;
  d: path("M17.5 21.5v-3h-3v-1h3v-3h1v3h3v1h-3v3zM4 19V5h3.385V2.77h1.077V5h5.153V2.77h1V5H18v7.33q-.25-.016-.5-.016t-.5.017v-1.715H5V18h7.289q0 .25.017.5t.063.5z");
}

</style>
