<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="put2mzb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:copy-all-outline-sharp" /></template>
<style>
.put2mzb0m {
  fill: currentColor;
  d: path("M3 18.5v-2h2v2zM3 15v-2h2v2zm0-3.5v-2h2v2zM6.5 22v-2h2v2zm.5-4V2h13v16zm2-2h9V4H9zm1 6v-2h2v2zm-7 0v-2h2v2zm10.5 0v-2h2v2zM3 8V6h2v2zm10.5 2");
}

</style>
