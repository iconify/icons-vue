<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qmo-mnbwk.css';
import '../../css/v/v920rdbob.css';
import '../../css/m/ms12apbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qmo-mnbwk"/><path class="v920rdbob"/><path class="ms12apbye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:court-house" /></template>
