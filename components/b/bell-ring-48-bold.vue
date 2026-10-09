<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxk_vcban.css';
import '../../css/f/fy_4q-bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wxk_vcban"/><path class="fy_4q-bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-ring-48-bold" /></template>
