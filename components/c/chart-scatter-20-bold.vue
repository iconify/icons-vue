<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd5r-ktwc.css';
import '../../css/u/u81anactb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qd5r-ktwc"/><path class="u81anactb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-scatter-20-bold" /></template>
