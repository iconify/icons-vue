<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxo5tubhm.css';
import '../../css/c/cw-sa1-6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mxo5tubhm"/><path class="cw-sa1-6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:camera-off-48-bold" /></template>
