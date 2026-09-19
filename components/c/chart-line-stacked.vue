<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4v9by9zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n4v9by9zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-line-stacked" /></template>
