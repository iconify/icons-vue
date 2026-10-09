<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8nquq1lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e8nquq1lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:family-48-bold" /></template>
