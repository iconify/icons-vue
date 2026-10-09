<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgzdi_vdo.css';
import '../../css/w/wfeynzbws.css';
import '../../css/r/rg22j5bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qgzdi_vdo"/><path class="wfeynzbws"/><path class="rg22j5bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cabin-48" /></template>
