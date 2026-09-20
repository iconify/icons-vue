<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/s/srxr8c13n.css';
import '../../css/i/iloc7qlea.css';
import '../../css/n/ntwgbdcqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="srxr8c13n"/><path class="iloc7qlea"/><path class="ntwgbdcqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:accessibility-linear" /></template>
