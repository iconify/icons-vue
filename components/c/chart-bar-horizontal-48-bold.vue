<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7lr-0b7o.css';
import '../../css/h/haai3or5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t7lr-0b7o"/><path class="haai3or5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bar-horizontal-48-bold" /></template>
