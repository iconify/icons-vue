<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qf26nbclk.css';
import '../../css/o/ojxizkvjf.css';
import '../../css/g/gr2myqbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qf26nbclk"/><path class="ojxizkvjf"/><path class="gr2myqbwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:body-soap" /></template>
