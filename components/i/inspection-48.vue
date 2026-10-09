<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbnuryord.css';
import '../../css/d/ddoez_smv.css';
import '../../css/z/z36fjojcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tbnuryord"/><path class="ddoez_smv"/><path class="z36fjojcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:inspection-48" /></template>
