<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wdhm326bq.css';
import '../../css/a/ahcwsvb2k.css';
import '../../css/l/lgdpnsvji.css';
import '../../css/o/oiw242cpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wdhm326bq"/><path class="ahcwsvb2k"/><path class="lgdpnsvji"/><path class="oiw242cpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-2-line-duotone" /></template>
