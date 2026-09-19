<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gw-3o2bdq.css';
import '../../css/t/t8wqp2bay.css';
import '../../css/x/xb0hh6bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gw-3o2bdq"/><path class="t8wqp2bay"/><path class="xb0hh6bzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:doughnut" /></template>
