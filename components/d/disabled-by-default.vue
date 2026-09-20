<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfcf36b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:disabled-by-default" /></template>
<style>
.qfcf36b5b {
  fill: currentColor;
  d: path("m8.4 16.289l3.6-3.6l3.6 3.6l.688-.689l-3.6-3.6l3.6-3.6l-.688-.689l-3.6 3.6l-3.6-3.6l-.689.689l3.6 3.6l-3.6 3.6zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
