<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc42tcp8f.css';
import '../../css/q/qol5o9b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xc42tcp8f"/><path class="qol5o9b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-pie-slice-48" /></template>
