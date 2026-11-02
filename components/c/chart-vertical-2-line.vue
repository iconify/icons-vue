<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhkkm6b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhkkm6b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-vertical-2-line" /></template>
