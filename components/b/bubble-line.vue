<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pchas7bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pchas7bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bubble-line" /></template>
