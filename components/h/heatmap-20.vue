<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwqk5_x8u.css';
import '../../css/k/kmpgrepgc.css';
import '../../css/m/mhu9q7s7p.css';
import '../../css/r/rgdy2_pio.css';
import '../../css/r/rb8emcc-u.css';
import '../../css/v/v7_5v7b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mwqk5_x8u"/><path class="kmpgrepgc"/><path class="mhu9q7s7p"/><path class="rgdy2_pio"/><path class="rb8emcc-u"/><path class="v7_5v7b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heatmap-20" /></template>
