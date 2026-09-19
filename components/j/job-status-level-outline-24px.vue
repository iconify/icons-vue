<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vka6x62mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vka6x62mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:job-status-level-outline-24px" /></template>
