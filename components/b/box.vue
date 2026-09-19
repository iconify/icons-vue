<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksf_1h48q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksf_1h48q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:box" /></template>
