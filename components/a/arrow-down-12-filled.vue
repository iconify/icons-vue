<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rqeiaacca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-12-filled" /></template>
<style>
.rqeiaacca {
  fill: currentColor;
  d: path("M6 1.5a.75.75 0 0 1 .75.75v5.94l1.97-1.97a.75.75 0 0 1 1.06 1.06l-3.25 3.25a.75.75 0 0 1-1.06 0L2.22 7.28a.75.75 0 1 1 1.06-1.06l1.97 1.97V2.25A.75.75 0 0 1 6 1.5");
}

</style>
