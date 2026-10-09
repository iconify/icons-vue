<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpeu_j1mo.css';
import '../../css/m/mkzcfdbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tpeu_j1mo"/><path class="mkzcfdbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crosshair-48" /></template>
