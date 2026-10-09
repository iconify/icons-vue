<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8v4i5bxl.css';
import '../../css/x/xd4ug9z_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i8v4i5bxl"/><path class="xd4ug9z_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-label-48-bold" /></template>
