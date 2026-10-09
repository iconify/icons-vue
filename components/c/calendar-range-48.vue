<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pycxs8orj.css';
import '../../css/o/oy7flk86j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pycxs8orj"/><path class="oy7flk86j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-range-48" /></template>
