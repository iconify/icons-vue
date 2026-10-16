<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9ka3cc1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e9ka3cc1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:infrared-panel-48-bold" /></template>
