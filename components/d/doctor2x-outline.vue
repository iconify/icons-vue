<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngs197bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ngs197bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:doctor2x-outline" /></template>
