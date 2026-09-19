<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/omcml5byg.css';
import '../../css/r/r0-cyki5y.css';
import '../../css/y/yuyh56b1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="omcml5byg"/><path class="r0-cyki5y"/><path class="yuyh56b1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:battery-charging-01" /></template>
