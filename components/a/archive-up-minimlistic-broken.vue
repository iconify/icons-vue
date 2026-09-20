<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l-llhz78d.css';
import '../../css/t/t6vi4ublf.css';
import '../../css/n/nxeolsbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l-llhz78d"/><path class="t6vi4ublf"/><path class="nxeolsbrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-up-minimlistic-broken" /></template>
