<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9emokusn.css';
import '../../css/m/mpu2txpdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m9emokusn"/><path class="mpu2txpdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cow-48-bold" /></template>
