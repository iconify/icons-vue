<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9hp2_byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e9hp2_byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:equal-48-bold" /></template>
