<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-_a2ccer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-_a2ccer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-column-big-fill" /></template>
