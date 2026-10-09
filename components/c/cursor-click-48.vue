<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lstwdq_nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lstwdq_nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cursor-click-48" /></template>
