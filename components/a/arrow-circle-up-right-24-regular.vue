<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb7zww7xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-right-24-regular" /></template>
<style>
.cb7zww7xd {
  fill: currentColor;
  d: path("M13.49 9.5H8.75a.75.75 0 0 1 0-1.5h6.5a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-1.5 0v-4.639l-5.222 5.172a.75.75 0 0 1-1.056-1.066zM2 12c0 5.523 4.477 10 10 10s10-4.477 10-10S17.523 2 12 2S2 6.477 2 12m10 8.5a8.5 8.5 0 1 1 0-17a8.5 8.5 0 0 1 0 17");
}

</style>
