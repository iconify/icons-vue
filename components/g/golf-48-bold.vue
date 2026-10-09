<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxzo85ixz.css';
import '../../css/q/qyem97bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mxzo85ixz"/><path class="qyem97bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:golf-48-bold" /></template>
