<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lofwxvbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dataset" /></template>
<style>
.lofwxvbag {
  fill: currentColor;
  d: path("M7.5 16.5h3v-3h-3zm6 0h3v-3h-3zm-6-6h3v-3h-3zm6 0h3v-3h-3zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
