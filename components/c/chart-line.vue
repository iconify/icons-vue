<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg5b6wann.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tg5b6wann"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-line" /></template>
