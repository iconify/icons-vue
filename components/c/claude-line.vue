<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r89b4cerd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r89b4cerd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:claude-line" /></template>
