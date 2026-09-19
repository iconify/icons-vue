<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqjf0ebnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uqjf0ebnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cannabis" /></template>
