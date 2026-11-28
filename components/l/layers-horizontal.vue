<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nln0rx3xh.css';
import '../../css/i/i4ukgldfb.css';
import '../../css/m/mic-pmbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nln0rx3xh"/><path class="i4ukgldfb"/><path class="mic-pmbmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-horizontal" /></template>
