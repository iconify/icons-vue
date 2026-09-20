<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r91ymwjqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:full-coverage-outline" /></template>
<style>
.r91ymwjqk {
  fill: currentColor;
  d: path("M4.616 20q-.691 0-1.153-.462T3 18.384V8h1v10.385q0 .23.192.423t.423.192H18v1zm4-4q-.691 0-1.153-.462T7 14.385V4h15v10.385q0 .69-.462 1.153T20.385 16zm0-1h11.769q.23 0 .423-.192t.192-.423V5H8v9.385q0 .23.192.423t.423.192M10 12h4V7h-4zm5 0h4v-2h-4zm0-3h4V7h-4zm-7 6V5z");
}

</style>
