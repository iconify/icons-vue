<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdierubwu.css';
import '../../css/t/tte9pybuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jdierubwu"/><path class="tte9pybuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cpu-48-bold" /></template>
