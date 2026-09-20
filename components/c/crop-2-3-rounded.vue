<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhxy32tfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-2-3-rounded" /></template>
<style>
.lhxy32tfz {
  fill: currentColor;
  d: path("M8.616 21q-.691 0-1.153-.462T7 19.385V4.615q0-.69.463-1.152T8.616 3h6.769q.69 0 1.153.463T17 4.616v14.769q0 .69-.462 1.153T15.385 21z");
}

</style>
