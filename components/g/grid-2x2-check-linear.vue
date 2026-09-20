<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/duo8u5b0b.css';
import '../../css/s/s6deurbms.css';
import '../../css/k/kt_jy-ber.css';
import '../../css/f/frr67dw0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="duo8u5b0b"/><path class="s6deurbms"/><path class="kt_jy-ber"/><path class="frr67dw0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-check-linear" /></template>
