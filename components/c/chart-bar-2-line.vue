<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evhja831n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evhja831n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-bar-2-line" /></template>
