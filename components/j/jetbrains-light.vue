<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-llkv2cb.css';
import '../../css/k/kckc1iwlf.css';
import '../../css/v/vqe6txv6a.css';
import '../../css/y/yxzgilblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGwtcoKmtL" x1="8.5" x2="499.3" y1="503.5" y2="12.7" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-llkv2cb"/><stop offset=".996" class="kckc1iwlf"/></linearGradient><path fill="url(#SVGwtcoKmtL)" class="vqe6txv6a"/><path class="yxzgilblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jetbrains-light" /></template>
