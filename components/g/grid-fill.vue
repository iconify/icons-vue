<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsn74dpfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsn74dpfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-fill" /></template>
