<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7autacoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7autacoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:board-line" /></template>
