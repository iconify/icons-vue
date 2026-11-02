<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi8yzdm9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi8yzdm9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-pie-3-fill" /></template>
