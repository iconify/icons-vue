<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtf397bse.css';
import '../../css/x/xyb5vubsu.css';
import '../../css/w/wwtxgkniu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dtf397bse"/><path class="xyb5vubsu"/><path class="wwtxgkniu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lamp-48-bold" /></template>
