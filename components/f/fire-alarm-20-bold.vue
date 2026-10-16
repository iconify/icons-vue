<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpfh3ybpx.css';
import '../../css/m/mc7p0pbek.css';
import '../../css/r/rsgdkwbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xpfh3ybpx"/><path class="mc7p0pbek"/><path class="rsgdkwbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-alarm-20-bold" /></template>
