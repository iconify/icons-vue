<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h10k0p92q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h10k0p92q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brush-3-ai-line" /></template>
