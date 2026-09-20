<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qle2ntjgu.css';
import '../../css/q/qgo3xbcao.css';
import '../../css/p/pxi4ntbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qle2ntjgu"/><path class="qgo3xbcao"/><rect transform="rotate(44.97 12.113 1)" class="pxi4ntbrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:corkscrew-line-duotone" /></template>
