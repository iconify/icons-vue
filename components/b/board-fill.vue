<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_2-x0bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_2-x0bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:board-fill" /></template>
