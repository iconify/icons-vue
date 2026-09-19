<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpdmhbaas.css';
import '../../css/l/l1sro9b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpdmhbaas"/><path class="l1sro9b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:doughnut-chart" /></template>
