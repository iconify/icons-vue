<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt88iibqu.css';
import '../../css/n/nsbcuotwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wt88iibqu"/><path class="nsbcuotwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:calculator" /></template>
