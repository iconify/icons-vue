<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnzkxjk6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-capslock-badge" /></template>
<style>
.cnzkxjk6o {
  fill: currentColor;
  d: path("M7.712 16h8.577v-1H7.711zm.688-3.02L12 9.4l3.6 3.58l.689-.688L12 7.985l-4.288 4.307zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
