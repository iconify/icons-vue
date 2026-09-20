<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rnt97vblj.css';
import '../../css/s/sttdwq4fh.css';
import '../../css/e/ee7yz0sic.css';
import '../../css/w/wkk2wqcxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rnt97vblj"/><path class="sttdwq4fh"/><path class="ee7yz0sic"/><path class="wkk2wqcxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calculator-line-duotone" /></template>
