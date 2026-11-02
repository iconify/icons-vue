<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it_td9u6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it_td9u6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-3-ai-line" /></template>
