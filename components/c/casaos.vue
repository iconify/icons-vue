<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa4-7mbfv.css';
import '../../css/p/piuz0fbpu.css';
import '../../css/k/k2hdxcbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pa4-7mbfv"/><path class="piuz0fbpu"/><path class="k2hdxcbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:casaos" /></template>
