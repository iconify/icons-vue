<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td1t-5bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td1t-5bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:job-status-level-24px" /></template>
