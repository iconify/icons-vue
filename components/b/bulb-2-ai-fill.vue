<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_x1l4byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_x1l4byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-2-ai-fill" /></template>
