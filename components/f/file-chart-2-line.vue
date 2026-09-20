<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu5u_dbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu5u_dbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-chart-2-line" /></template>
