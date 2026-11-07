<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/ahcwsvb2k.css';
import '../../css/l/lgdpnsvji.css';
import '../../css/u/ux4dmub_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ahcwsvb2k"/><path class="lgdpnsvji"/><path class="ux4dmub_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-linear" /></template>
