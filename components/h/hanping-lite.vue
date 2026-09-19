<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rfp1oebvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hanping-lite" /></template>
<style>
.rfp1oebvy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.442 11.975c2.097 19.302 11.285 25.838 27.812 30.772m-8.695-30.772c-2.097 19.3-11.286 25.838-27.812 30.771M24 5.255v6.66m-18.5 0h37");
}

</style>
