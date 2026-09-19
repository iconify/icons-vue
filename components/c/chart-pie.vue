<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5u01abyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d5u01abyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:chart-pie" /></template>
