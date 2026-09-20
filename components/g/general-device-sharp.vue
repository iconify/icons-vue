<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw1_j2b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:general-device-sharp" /></template>
<style>
.qw1_j2b3t {
  fill: currentColor;
  d: path("M8 18V3h8v15zm0 3v-2h8v2z");
}

</style>
