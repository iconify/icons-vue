<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipu02zq8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipu02zq8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-3-ai-fill" /></template>
