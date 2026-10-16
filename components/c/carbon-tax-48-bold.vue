<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk4s-jblr.css';
import '../../css/q/qrg4uebsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qk4s-jblr"/><path class="qrg4uebsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-tax-48-bold" /></template>
