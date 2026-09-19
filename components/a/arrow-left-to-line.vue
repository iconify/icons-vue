<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vnp6a-b8y.css';
import '../../css/d/d56_pbcee.css';
import '../../css/w/w_l_yzbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vnp6a-b8y"/><path class="d56_pbcee"/><path class="w_l_yzbyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-left-to-line" /></template>
