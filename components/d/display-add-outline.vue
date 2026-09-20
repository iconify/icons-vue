<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsu3o9blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:display-add-outline" /></template>
<style>
.lsu3o9blj {
  fill: currentColor;
  d: path("M4 5v12zm5 15v-2H4.616q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h8.197q-.08.244-.119.485q-.04.24-.059.515H4.616q-.231 0-.424.192T4 5.616v10.769q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.423v-5.21q.28-.061.521-.15q.24-.089.479-.21v5.57q0 .69-.462 1.152T19.385 18H15v2zm9-11V6h-3V5h3V2h1v3h3v1h-3v3z");
}

</style>
