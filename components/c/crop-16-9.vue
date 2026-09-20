<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv4cavb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-16-9" /></template>
<style>
.mv4cavb3k {
  fill: currentColor;
  d: path("M5.616 16q-.691 0-1.153-.462T4 14.385v-4.77q0-.69.463-1.152T5.616 8h12.769q.69 0 1.153.463T20 9.616v4.769q0 .69-.462 1.153T18.384 16z");
}

</style>
