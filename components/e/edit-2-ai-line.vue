<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgipp0bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgipp0bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-2-ai-line" /></template>
