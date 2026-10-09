<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxvnz_b5x.css';
import '../../css/h/h8trvnbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uxvnz_b5x"/><path class="h8trvnbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-chart-48-bold" /></template>
