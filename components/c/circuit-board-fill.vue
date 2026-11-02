<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dggbul2sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dggbul2sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circuit-board-fill" /></template>
