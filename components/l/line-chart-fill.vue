<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz86vtb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz86vtb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:line-chart-fill" /></template>
