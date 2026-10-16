<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_xy3blpc.css';
import '../../css/l/lewmoqbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t_xy3blpc"/><path class="lewmoqbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-pie-slice-20" /></template>
