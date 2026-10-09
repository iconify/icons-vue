<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqbbhusyr.css';
import '../../css/q/qnl7h7qtq.css';
import '../../css/i/iciarnbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sqbbhusyr"/><path class="qnl7h7qtq"/><path class="iciarnbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:buoy-48" /></template>
