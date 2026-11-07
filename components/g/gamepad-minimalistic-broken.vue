<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uz9iye4tk.css';
import '../../css/a/a9nvjpbmz.css';
import '../../css/s/sdvb_kngq.css';
import '../../css/n/njaypgbkt.css';
import '../../css/j/jg20qzbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uz9iye4tk"/><path class="a9nvjpbmz"/><path class="sdvb_kngq"/><path class="njaypgbkt"/><path class="jg20qzbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-minimalistic-broken" /></template>
