<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/loam-qbtt.css';
import '../../css/t/tnfby2q5d.css';
import '../../css/p/pu97ujszu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="loam-qbtt"/><path class="tnfby2q5d"/><path class="pu97ujszu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-charge-minimalistic-line-duotone" /></template>
