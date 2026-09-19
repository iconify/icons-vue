<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbmlz2beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbmlz2beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-cured-decreasing-24px" /></template>
