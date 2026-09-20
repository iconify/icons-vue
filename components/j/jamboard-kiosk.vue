<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fla9b1bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:jamboard-kiosk" /></template>
<style>
.fla9b1bvv {
  fill: currentColor;
  d: path("M7 20v-1h4.5v-3H4.616q-.691 0-1.153-.462T3 14.385v-8.77q0-.69.463-1.152T4.615 4h14.77q.69 0 1.152.463T21 5.616v8.769q0 .69-.463 1.153T19.385 16H12.5v3H17v1z");
}

</style>
