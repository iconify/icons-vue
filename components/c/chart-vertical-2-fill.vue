<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4t3ysxce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4t3ysxce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-vertical-2-fill" /></template>
