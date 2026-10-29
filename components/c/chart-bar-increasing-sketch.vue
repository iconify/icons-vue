<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cur66cgez.css';
import '../../css/j/jlz57qpcn.css';
import '../../css/s/spe3eibot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cur66cgez wm-a"/><path class="jlz57qpcn wm-k"/><path class="spe3eibot wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-bar-increasing-sketch" /></template>
