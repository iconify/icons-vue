<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9fz9_l5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9fz9_l5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-bar-line" /></template>
