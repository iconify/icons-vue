<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pla2dab5a.css';
import '../../css/b/bkn4clyuz.css';
import '../../css/x/xj-p88xil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pla2dab5a"/><path class="bkn4clyuz"/><path class="xj-p88xil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:investigation" /></template>
