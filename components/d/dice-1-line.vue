<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g90d3kbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g90d3kbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dice-1-line" /></template>
