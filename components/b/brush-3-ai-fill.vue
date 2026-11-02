<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxmqqxb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxmqqxb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brush-3-ai-fill" /></template>
