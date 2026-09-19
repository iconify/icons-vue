<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv66cgbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qv66cgbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:job-status-level2x-outline" /></template>
