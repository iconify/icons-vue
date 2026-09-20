<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_u1_2b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-month-outline-sharp" /></template>
<style>
.z_u1_2b1i {
  fill: currentColor;
  d: path("M11 14v-2h2v2zm-4 0v-2h2v2zm8 0v-2h2v2zm-4 4v-2h2v2zm-4 0v-2h2v2zm8 0v-2h2v2zM3 22V4h3V2h2v2h8V2h2v2h3v18zm2-2h14V10H5zM5 8h14V6H5zm0 0V6z");
}

</style>
