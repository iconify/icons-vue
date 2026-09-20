<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qxk09zbgn.css';
import '../../css/t/tt7ewmbov.css';
import '../../css/w/w6ht4_aov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qxk09zbgn"/><path class="tt7ewmbov"/><path class="w6ht4_aov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:bell-off" /></template>
