<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbzdxvbap.css';
import '../../css/k/kc18vwbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mbzdxvbap"/><path class="kc18vwbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-air-balloon-48-bold" /></template>
