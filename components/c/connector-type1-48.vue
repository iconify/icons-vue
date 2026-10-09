<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg-biwbzh.css';
import '../../css/n/nrf_j2jrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xg-biwbzh"/><path class="nrf_j2jrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-type1-48" /></template>
