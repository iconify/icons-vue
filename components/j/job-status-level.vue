<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l26-ium8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l26-ium8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:job-status-level" /></template>
