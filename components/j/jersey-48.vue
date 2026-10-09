<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc9z0ibda.css';
import '../../css/m/m_t120kfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uc9z0ibda"/><path class="m_t120kfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jersey-48" /></template>
