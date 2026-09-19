<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k8mf6ccnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amd-link" /></template>
<style>
.k8mf6ccnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.614 33.614l9.25 9.25v-37h-37l9.25 9.25h18.5zm-18.5 0V19.55l-9.229 9.228l-.021 14.086l14.085-.022l9.228-9.228z");
}

</style>
