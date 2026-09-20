<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv5o5wirv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv5o5wirv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-2-ai-line" /></template>
