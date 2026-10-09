<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmj85obju.css';
import '../../css/o/oj51yuuri.css';
import '../../css/d/dede64x5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zmj85obju"/><path class="oj51yuuri"/><path class="dede64x5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:global-warming-48" /></template>
