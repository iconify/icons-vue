<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svn20mxkr.css';
import '../../css/l/l-f6ssbaf.css';
import '../../css/r/ra1t7sbvx.css';
import '../../css/q/qam-_kbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="svn20mxkr"/><path class="l-f6ssbaf"/><path class="ra1t7sbvx"/><path class="qam-_kbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cottage-48-bold" /></template>
