<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di3t_vcmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="di3t_vcmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-pie" /></template>
