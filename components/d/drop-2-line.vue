<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-ni44i5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-ni44i5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drop-2-line" /></template>
