<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sa0bz32lw.css';
import '../../css/x/xslfg2evh.css';
import '../../css/g/g5srfcchm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sa0bz32lw"/><path class="xslfg2evh"/><path class="g5srfcchm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-down-to-line" /></template>
