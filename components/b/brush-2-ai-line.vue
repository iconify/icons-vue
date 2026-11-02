<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir4zf7qyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir4zf7qyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brush-2-ai-line" /></template>
