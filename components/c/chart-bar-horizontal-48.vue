<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv2p86eoi.css';
import '../../css/i/ietxivbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tv2p86eoi"/><path class="ietxivbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bar-horizontal-48" /></template>
